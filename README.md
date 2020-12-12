# Employee Roster Generator

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

## Description 
The goal of this project was to allow the user to generate a html page that displays information about all the employees that work for a company.  The program generates a new file that is already formated and includes all the data the user inputed.  This project was built using node.j\ and includes the npm package inquirer to allow the user to interact with the program via the commandline.   

## Table of Contents
  
* [Installation](#installation)
* [Usage](#usage)
* [Walkthrough](#walkthrough)
* [Tests](#tests)
* [License](#license)
* [Questions](#questions)
  
  
## Installation
** This project requires node.js so make sure that is installed on your system before doing anything else. **

* Step 1: Navigate to the directory you want to store the project. Clone this your repository to your local computer using the command below. 
```bash
git clone https://github.com/MarkMulligan97/readmeGenerator.git
```

* Step 2: Use the command line to navigate to the directory that you cloned the project.
Example:
```bash
cd directory/projectdirectory
```

* Step 3: Install the npm package dependencies from the package.json file.
```bash
npm install
```

* Step 4: While in the project directory, run the program using node using the command below.
```bash
node app.js
```
## Usage 
After installing the project and all the required npm packages, run the project in your command line using node.  Make sure to be in the project directory.
```bash
node app.js
```
1.  Answer all the questions that are prompted to you in the command line.  
2.  After all the questions have been answered, a team.html file will be generated in the output folder.
3.  Also included in the output folder is an assets folder that contains all the css and images that go along with the generated html page.

![Project Screenshot](./images/employeeGeneratorTop.png)

## Walkthrough 
[Video Demo](https://youtu.be/Q8pTRk2yF5w)

Example team.html generated using this project:
[click here](./output/team.html)

## Tests
Tests for this project are included in the test folder.  These tests are desigened to make sure all the classes are working properly.  

* Make sure jest is installed using npm.
* To run the tests, run 'npm run test' in the command line.
```bash
npm run test
```

## License
This project is liscensed under an Apache license.

For more info, checkout this link:
https://opensource.org/licenses/Apache-2.0

## Questions
[My Github](https://github.com/MarkMulligan97) || mark.mulligan.jr1@gmail.com

#### How to Contact Me
Feel free to reach out to me if you have any questions about this project.  You can email me using the email listed above or can go to my github page to view my other projects and portfolio.

© Mark Mulligan 2020 All Rights Reserved.