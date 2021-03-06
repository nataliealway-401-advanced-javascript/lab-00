# Code401: lab-00 Pre-work Deployment Workshop

### Author: Natalie Alway

### Links and Resources
* [submission PR](https://github.com/nataliealway-401-advanced-javascript/lab-00/pull/1)
* [travis](https://travis-ci.com/nataliealway-401-advanced-javascript/lab-00/builds/143196062)
* [front-end](https://nataliealway-lab-00.herokuapp.com/)

#### Documentation
* [jsdoc](https://nataliealway-lab-00.herokuapp.com/docs/)

### Modules
#### `pol.js`
##### Exported Values and Methods

###### `isAlive(dead) -> boolean`
The isAlive() method returns a boolean based on the arg sent in.

### Setup
#### `.env` requirements
* `PORT` - Port Number

#### Running the app
* `npm start`
* Endpoint: `/`
  * Returns true or false
* Endpoint: `/docs`
  * Renders Developer Documentation
  
#### Tests
* Unit Tests: `npm run test`
* Lint Tests: `npm run lint`
* Assertions Made
  * Assert that isAlive() properly returns a boolean
* Assertions Remaining
  * placeholder for notes to TAs about tests I haven't written yet

#### UML  
*(the following image is from CodeFellows's Deployment Tutorial)*

![UML Diagram](whiteboard.jpg)