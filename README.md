# template-engine-employee-summary
This is a software engineering team generator command line application. The application will prompt the user for information about the team manager and then information about the team members. The user can input any number of team members, and they may be a mix of engineers and interns. When the user has completed building the team, the application will create an HTML file that displays a nicely formatted team roster based on the information provided by the user. 

## Getting Started
### Prerequisites
* There is a `package.json`, so make sure to `npm install`.

## Running the tests
* Run the tests with `npm test` at any time.

## Deployment
### User input
The project will prompt the user to build an engineering team. An engineering
team consists of a manager, and any number of engineers and interns.

### Roster output
The project will generate a `team.html` page in the `output` directory, that displays a nicely formatted team roster. Each team member should display the following in no particular order:

  * Name

  * Role

  * ID

  * Role-specific property (School, link to GitHub profile, or office number)

## Built With
* [jest](https://jestjs.io/) - running the provided tests
* [inquirer](https://www.npmjs.com/package/inquirer) - collecting input from the user
