# aos

# Project Info

## Purpose

To create automated test to test basic business critical
functionality of an eCommerce web application Advantage Online Shopping.
The project was given as a capstone project and final phase of
course for Software Quality and Test Automation during my studies at
Canadian College of Technology and Business(CCTB)

# Technology stack

### Application Environment
(where tests are developed)
https://advantageonlineshopping.com/#/
- Localhost version can be installed and used as well
- Local host URL : http://localhost:8080/

### Automation Environment
(Tools,Technologies used to develop automated tests)


- _IDE:_ PyCharm
- _Automation Framework:_ Selenium Webdriver
- _Language:_ Python
- _Browser:_ Chrome
- _Source Control:_ Git/GitHub
- _Data:_ Python Faker library



### Executive Environment

- Jenkins on AWS EC2 linux instance with SSH-key based secure connection
to GitHub repository to pull and run the selenium scripts
- Local running the tests in PyCharm

### Project Structure

- aos_tests.py : all test cases
- aos_methods.py : all methods used in test cases like create_new_user
- aos_locators.py : data used in tests


### Project Management

- Automated tests are developed based on Manual test cases 
using Jira weekly Sprints
- Manual tests Cases are documented and managed via Jira Tasks
- Manual and Automated tests development is managed vis Jira Issues


 





