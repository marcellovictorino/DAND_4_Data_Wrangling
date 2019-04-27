## Code

1. Remove irrelevant variables from dataframe: ['jobpost', 'Eligibility', 'Audience', 'Notes', 'AboutC', 'Attach', 'AnnouncementCode', 'JobDescription', 'JobRequirment', 'Salary', 'ApplicationP']

2. Aggregate variables with redundant values:
    - Term: 'Full/Part-time', 'Full-time','Part-time','Contract', 'Other'
    - Start Date: ASAP, Other
    - Duration: 'Permanent', 'Up to 1 Year', '2-5 years', 'Other
    - Location: Main cities
    - Opening Date: fix formatting (extra blank space)
    - Deadline: rolling, rolling groups
    - Title: aggregate positions

3. Datatype:
    - date: object -> datetime

4. Standardize columns name (string formatting)