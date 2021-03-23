# QA_automation_certification_postman
This is a repository of QA Automation Certification API testing for the web page https://todoist.com/

# Setup

- Clone this repository
  - Navigate to https://github.com/MiguelMoraa/QA_automation_certification_postman.git
  - Click on Clone or Download and copy the project url
  - Open the command line terminal
  - Navigate to the desired directory for the project
  - Execute `git clone [ProjectURL]`
- Run command `npm init`
- Run command `npm install newman`
- Run command `npm install newman-reporter-htmlextra`


# Project Structure

    - collections (Store a json file with postman collections)
    - environment ((Store a json file with postman environment data))
    - reports (Store de html report from de test cases)
    package.json (Store dependencies and can be used to set scripts)

## Running the tests

- To run test cases use `npm run newman-test`
- To run the tests with the final report use `npm run newman-test-report`
