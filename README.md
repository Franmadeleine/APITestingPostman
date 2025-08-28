🧪 API Testing Project with Postman – Practice Collection

This project is a comprehensive API testing suite developed using Postman, focused on validating endpoints of a fictional application. The structure includes 45 independent requests, organized into five folders: User, Articles, Profile, Tags, and Comments.

Each request was designed to simulate real-world scenarios, covering positive flows, negative cases, and edge conditions. Tests were implemented in Postman's Tests tab, with validations that include:

✅ Status code verification 

⏱ Response time measurement 

📦 Response body structure and property checks 

⚠️ Error message and validation feedback

🔍 Project Highlights

All requests are independent, with no dependency on prior executions.

Pre-request scripts were used at the collection level to simulate actions such as user registration, article creation, and comment posting.

Automated cleanup: articles created during testing are deleted using functions written in the pre-request scripts, preventing database clutter.

Failed cases were documented with bug reports in Jira, following QA best practices.

The collection was executed multiple times without a selected environment — all requests passed successfully.

📂 Collection Structure

Postman Practice [Francesca Madeleine]

├── User

├── Articles

├── Profile

├── Tags

└── Comments

📌 Sample Endpoints Tested

POST /users/login – Successful login and error scenarios

POST /users – Sign-up with various invalid inputs

GET /articles – Feed and tag-based filtering

DELETE /articles/:slug – Authorization and ownership validation

POST /profiles/:username/follow – Follow/unfollow functionality

POST /articles/:slug/comments – Comment creation and deletion with permission checks

🛠 Tools and Skills Applied
Postman (Collections, Tests, Pre-request scripts)

RESTful API principles

Exploratory and negative testing

Jira (bug tracking and documentation)

JSON, HTTP methods, status codes

Test documentation and case design
