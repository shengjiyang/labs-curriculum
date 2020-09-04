# Sprint Challenge: Sprint 1

## Objectives

- Student can articulate breaking down a release into individual tasks.
- Student can accurately defend scope or timeline of an individual task
- Students will be able to articulate tradeoffs for architectural and design decisions

## Prompt 1 - Communicating Process

Hiring managers don't just want to see what you built, they want to see the reasoning behind it. Here are some questions surveyed hiring managers said they would ask about a project:

- "How did you decide what to build?"
- "Why is this feature important?"
- "Was this a good choice? What would you do differently if you had to do it over again?"

We took these questions and cooked them into your labs experience. Please answer the following questions as you would in an interview. Remember, hiring managers care about the **process** and the **why** of building something even more than the what.

### Questions you need to answer

1. Describe your **process** of breaking a release into user stories.
    - **Step 1**: The team should begin by asking itself the question, what is this application, program, website, etc. supposed to do?
    - **Step 2**: Based on the answer or answers to the question in **Step 1** begin by jotting down a single or multiple broad user stories.
    - **Step 3**: Take the broad user story or stories and itteratively break each story down until each user story is defined as a discrete unit linked to any and all prerequisite stories.
2. Choose a user story. Describe your **reasoning** as you broke down that particular user story into individual tasks.
<br\>
**Users should be able to compare cities based on weather (by season) and see visualizations of the comparisons.**
    - **Steps**
        - Query data science API to gather relevant info about cities
        - Determine what weather information to include (avg temp? avg precipitation? seasonal?)
        - Create a function to generate visuals of above weather stats for a city and return JSON output of the visualization
        - Deploy function into FastAPI
        - Test function locally via Docker (on each DS student's machine)
        - Deploy function to AWS 
        - Test function in AWS deployment


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;When the Data Science team broke this user story into individual steps, we essentially drew on our experience in building Flask apps using data from third-party APIs. We simply applied this to the specific case of dealing with weather data and swapped out Flask for FastAPI and Heroku for AWS. We also accounted for the fact that the template came with a Docker image. Step 5 is included both to stay in line with what Ryan Herr expects of us and to act as a refresher for those of us who forgot pretty much everything we learned about Docker in Unit 3.

3. How long do you think the above user story will take to complete? Explain your reasoning.

Without including the predictive model elements of the task: roughly 1.5 weeks
    - 1 day to figure out the API and pull the minimum amount of data to meet the project requirements
    - 1-2 days to clean the data and extract the approprate data from it.
    - 1-2 days to build working functions for displaying the appropriate single-value and visualization data.
    - 2-3 days to get frustrated with Amazon Web Service if it's as much of a pain as Heroku was
    
Including the predictive model elements of the task: roughly 2.5 - 3.0 weeks
    - All of the above steps
    - Added time to attempt simple linear and tree-based models
    - Added time to research and apply time-series analysis techniques to model
    - Added time to build more functions and more FastAPI routes needed to spit back future predictions

## Prompt 2 - Communicating Technical Decisions

On the job, you'll be making technical decisions every day. Hiring managers want to see how you make a choice and how you communicate your decisions. Here are some examples of questions they might ask about one of your projects in an interview:

- "What kind of database did you choose and why?"
- "Why did you use X to do Y?"

These sorts of questions inform your entire labs experience. You made a few technical decisions this week. We want to see how you would communicate them in an interview.

### Questions you need to answer

1. Describe a technical decision you made. How did you make that decision?

My Data Science colleagues and I decided to use a Pip Environment while including a global requirenments.txt file.


2. What are some of the risks given the decision you made?

Potentially slower API calls and slower app performance.

3. What challenges do you foresee in using the architecture your team selected?

One of us forgetting to update the requirenments.txt file, or conflicting versions of Python for Pipenv users.

## Prompt 3 - Professional Development 

### [Power Statements](https://learn.lambdaschool.com/cr/module/recQUR9bWxvLBJknr](https://learn.lambdaschool.com/cr/module/recQUR9bWxvLBJknr))

This lesson we reinforced how to turn your responsibilities and tasks into power statements. To practice, write a few power statements you intend to use in your LinkedIn profile. Before writing those statements, ensure your LinkedIn has all the following content checked off.

Add a link to your Linkedin in your sprint challenge submission document.

[My LinkedIn](https://www.linkedin.com/in/samuel-swank/)

## Personal and Contact Information:

- [ ]  First and last name are added to profile
- [ ]  Created a [shortened, unique](https://www.linkedin.com/help/linkedin/answer/87/customizing-your-public-profile-url?lang=en) LinkedIn URL
- [ ]  Profile picture is clear, shows my face (not a selfie), and is in front of a professional background
- [ ]  Listed title, `i.e. iOS Developer`, below name with any keyword associations included.  **For example: “Data Scientist, with a passion for data visualizations and open-source code”**
    - [ ]  Title **does not** pull from my current position (this is a LinkedIn default, must manually change), unless that position is relevant to the tech industry

## About Section

- [ ]  Wrote a minimum of 3 sentences to describe my technical skills, background, interests, and passions. (Also feel free to include key professional accomplishments.)

## Experience Section

- [ ]  Listed all, or at least the last 3-5 years of previous professional roles
- [ ]  Included 2-4 power statements for each experience listed (okay to copy and paste from resume)
    - [ ]  Power statements for each experience [are bulleted](https://www.linkedin.com/pulse/update-how-add-bullet-points-your-linkedin-profile-erin-dore-miller/), not in paragraph form.
    - [ ]  Listed responsibilities in bullet point format (I **did not** leave in paragraph format). If you use Windows, hold down the ALT key and type 0149 on the keypad. Release the ALT key and the bullet point will appear. On a Mac, press Opt + 8 on the keyboard.
    - [ ]  Started each bullet point with [an action verb](https://docs.google.com/document/d/1wZkDPBWtQZDGGdvStD61iRx_jOWVlIyyQl9UOYHtZgA/edit?usp=sharing) and **did not** re-use phrases such as:  `Assisted with...` `Worked on...` `Helped with...`  (`Solely responsible for...`)
    - [ ]  Described past projects in past tense and current projects in present tense
    - [ ]  Did not use pronouns such as: I, we, they, you, me, us

## Education

- [ ]  Listed all education and relevant certifications: including name of the institution, degree type, and date the degree was received or will be received `i.e. May 2020` or `Expected July 2025`
    - [ ]  I **did** link to Lambda School properly (Lambda logo saved)

## Skills

- [ ]  **Listed** all technical skills, methodologies, and platforms with strongest skills [pinned at the top of the list](https://www.linkedin.com/help/linkedin/answer/35265/display-order-of-skill-endorsements?lang=en)

With all the above checked off, go to LinkedIn's "Accomplishments" section to add a project. Articulating the tasks or project work you're doing publicly on a platform like LinkedIn can help you gain visibility! LinkedIn is designed to produce better results, recommendations, and engagement for users who have thorough profiles and who upload content. If you haven't done so already, write a few power statements as well as a project description to populate those content fields and describe your project on LinkedIn.

This is also a good time to add your fellow labs teammates as connections so that you can add them as "creators" on the project.

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/399b50ea-bb7b-4218-977b-844d86a0203d/Screen_Shot_2020-07-23_at_10.35.42_AM.png](https://tk-assets.lambdaschool.com/d6b22266-d5f7-4949-8db9-8fe5f7ae1f4f_Screen_Shot_2020-07-23_at_10.35.42_AM.png)

Here's the checklist you'll want to complete for projects:

## Projects (Under "Accomplishments")

- [ ]  **Listed** title for Labs projects
- [ ]  **Included one sentence** to describe what the project does
    - [ ]  I **did not** use the phrase `This project was...` or `This project is...` in description
    - [ ]  I **did not** use more than one sentence to describe the project
- [ ]  **Listed** the tech stack used for each project (see below for example)
- [ ]  **Listed 2-3 power statement bullets** highlighting my responsibilities on project
- [ ]  **Did not** use the words "capstone" "Lambda Labs" or "School" project

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/18ad1d52-5679-4f4e-80bc-aa0341034f93/Untitled.png](https://tk-assets.lambdaschool.com/4f07d726-0a78-4014-82f4-dd56a02f21bc_Untitled2.png)

## [Sprint Challenge Rubric](https://www.notion.so/863354e030274baf99983cfee357d4d1)
