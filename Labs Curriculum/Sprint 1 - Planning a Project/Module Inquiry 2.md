# Module Inquiry 2

## Questions

1. What technical choices did you make today?
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;My Data Science colleagues and I decided to use a Pip Environment while including a global requirenments.txt file.
2. Pick two technical choices you're happy with. What was your thought process as you made those choices? What did you consider and what did you decide against?
    - Take a moment to think about the advantages in choosing the route that you did.
        - Any member of our team would be able to run the files in the repository regardless of whether they were using Conda or a Pip Environment.
    - Now take a moment to consider the disadvantages.
        - The numer of dependencies pushed to AWS may lead to slower API calls and slower resultant app performance.
3. In one or two sentences, summarize why you ultimately made the choice you did.
    - Aaron set things up this way, and it seemed reasonable, so we rolled with it.
4. Extracting useful conclusions from your process: 
    - According to your understanding, what makes a good technical choice?
        - Accounts for its effect on the user
        - Accounts for its effect on the developers
        - Ensures that the architecture is simple enough to be understood while being sophisticated enough to get the job done.
        - Allows for generalizability in application.
        - Ensures security
        - Ensures stability
