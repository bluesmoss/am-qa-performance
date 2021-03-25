# QA Backend Automation

This project belongs to the 3rd assessment of the QA automation certification of Wizeline Academy

## Development Setup

### Prerequisites


- Install [Node.js](https://nodejs.org/en/ "Node.js") which includes [Node Package Manager](https://www.npmjs.com/get-npm "Node Package Manager")

- Create a [TODOIST](https://todoist.com/ "TODOIST") account and get the API TOKEN

### Installing

- Clone the project 


```
git clone git@github.com:bluesmoss/am-qa-performance.git
```

- Navigate to the  am-qa-backend directory

```
cd am-qa-performance
```

- Install dependencies

```
npm install
```

- Run the command to create the folder reports

```
npm run init
```

-  Run the command to define the token API

```
export TOKEN="YOUR_TOKEN_HERE"
```

## Running the tests

You can execute the following commands to run the tests:

- Run the tests and get the report in JSON and HTML:

```
npm run test
```

- Run the tests for the staging environment and get the report in JSON and HTML:

```
npm run test-staging
```

- Run the tests for the production environment and get the report in JSON and HTML:

```
npm run test-production
```

The HTML reports will be saved in the folder ./results  then you can open them with any browser.

Cooked with 💙 by 👽 @bluesmoss