# Team Profile Generator

## Description

I have built a software engineering team generator command line application. The application prompts the user for information about the team manager and then information about the team members. The user can input any number of team members, and they may be a mix of engineers and interns. It is a Node CLI that takes in information about employees and generates an HTML webpage that displays summaries for each person.

As a manager
I want to generate a webpage that displays my team's basic info
so that I have quick access to emails and GitHub profiles

## Table of Contents

*[Installation](#installation)
*[Usage](#usage)
*[Contributing](#contributing)

## Installation

  1. Include the package folder within your project directory.
  2. Open your terminal to your current project directory.
  3. Type "node app.js" in the console.
  4. You will then be asked to input information regarding the team member you would like to add to the page.
  5. Once questions are successfully answered, a generated README.md will be created and placed in your project's directory.

## Usage

1. The user is first asked to select the role of the person they would like to add to the page.
2. Subsequently, the user will be asked to provide their name, id, and email regardless of the role-type.
3. Next the user will be asked to answer a role-specific question. For managers, the user will be asked to input the manager's office number. For engineers, the user will be asked to input the engineer's github username. Lastly, for interns, the user will be asked to input the school at which they attend. 
4. Following these steps, an html file called `team.html` will be generated in the `output` directory. 
5. Open `team.html` to see user input beautifully displayed in the browser.

It should look something like this:

![Employee Summary 1](./Assets/10-OOP-homework-demo-1.png)
![Employee Summary 2](./Assets/10-OOP-homework-demo-2.png)

## Contributing

Keaton Smith

