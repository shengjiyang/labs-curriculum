# Module Inquiry 1

## Questions

For context, this inquiry is associated with the Citrics project, with Parth Shah acting as stakeholder.

### 1. What questions did you ask your stakeholder that helped in breaking down your tasks?

    - What constitues a city? *It needs to be large enough for you to be able to find data.*
    - Is there a cap on population? *At least 50,000 people to start with.*
    - How do we handle places like New York with multiple burroughs, districts etc. *Count mega cities like New York as single entities to begin with. As the project progresses you can split them up if you wish.*
    - What metrics are most important to you that we include for each city? *Rent Price, Weather, and Job Industy*
    - Please be more specific with regards to *Job Industry*. *Cricket Noises*
    
### 2. What user stories did you draw from to create your product roadmap? List them below.

#### DS
- Users (web) should be able to view JSON endpoint of cities (current) metrics.
- Users (web) should be able to view JSON endpoints of a city's statistics (MVP: rent price, weather, job industry)
- Users should be able to compare cities based on weather (by season) and see visualizations of the comparisons.
- Users should be able to compare cities based on job growth rate and see visualizations of the comparisons.
- Users should be able to compare cities based on rent prices and see visualizations of the comparisons.

#### Web
- Users should be able to search for a city
- Users should be able to select up to 3 cities to compare
- User can view report of various city statistics after searching for desired city
- User can view the compare list
- User can add item(s) to compare list
- User can remove item from compare list

### 3. Select your favorite user story. What are the tasks that need to be accomplished in order to ship that particular user story?
Users (web) should be able to view JSON endpoints of a city's statistics (MVP: rent price, weather, job industry)

The appropriate data need to be found and scraped if needed. These data need to be organized into a Pandas DataFrame. Either that DataFrame itself or a series of visualizations need to be converted to JSON format, and routes need to built into a FastAPI with Doc Strings so that the Web Developers will have access to them and know how to use them.

    - What did you do well in this task breakdown process? What were some challenges?
        I will let others be the judge of this.
    
### 4. After what you've learned in this process, given a new product roadmap, how would you approach it differently? What would you change about the way you go about breaking down individual tasks?

At this stage, I would not really change anything.
