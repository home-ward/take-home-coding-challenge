## Backend Take Home Coding Challenge

Please organize, design, test, document, and deploy your code as if it were going into production.

### Challenge Description

We currently have an API set up to return information about a customer's application. It includes the name of
the real estate agent who represents the customer. We want to hold more information about the real estate agent and
display this information on our frontend.

Create an API that returns real estate agent information for display on the frontend. We need to see the agent's contact
information, brokerage name, and location (city, state). We will need the ability to return a specific real estate
agent that is already connected to a customer. We will also need to be able to return a list of agents based on a
specific location.

### Make sure to include:
- Data models (You can add more data models and add to the current models available)
- Endpoints
- Any utility functions needed

### Requirements
- Please code in the language you are most comfortable with. You do not need to know python to complete this project.
- Do not spend more than 2 hours on this project. It does not need to be complete before we review your work. 
- Use object oriented programming design. 
- Write a simple REST API.
- Include error handling and unit tests when applicable.
- Make sure your code is well-structured. Organize the code in a way you are most familiar with.

### How to Submit
- Upload your repository on Github/Bitbucket.
- Send the link to your repository to josh@homeward.com.
- We will schedule a time to review your work.

### Current Application Model
- Customer
- Purchasing address (text field)
- Application approved (boolean)
- Agent name

### Current Customer Model
- Name
- Email
- Phone number
- Current address (text field)
