# server-deployment-practice

## Resub Comments
Resubmit when you can. Note on the README just need to add links of the Pull Request, Github Actions, and Deployed site. Along with how to run your app.

## Dev Branch Link 
https://klace-https://klace-server-deploy-prod.herokuapp.com/server-deploy-dev.herokuapp.com/

## Main Branch Link
https://klace-server-deploy-prod.herokuapp.com/

## Pull Request Link
https://github.com/klace650/server-deployment-practice/pull/1

## Git Hub Actions Link
https://github.com/klace650/server-deployment-practice/actions

## How to Run:

``npm i``
Create ``.env``
First line of ``.env`` add ``PORT=3000`` - or whatever port ya want!
``npm start``

### Importing and Exporting Modules

If one module **exports** a function or an object ...

```javascript
// person.js
const person = {};

person.walk = function() {
  return 'walking';
}

module.exports = person;
```

Another module can **import** and use that function or object

```javascript
const human = require('./person.js'))
console.log( human.walk() );  // prints 'walking'
```

### CI/CD - Continuous Integration and Deployment

In your lab today, you'll be doing a full "professional" deployment using 2 branches, PR's, and a continuous process to get your code deployed.

You will repeat this process for every server based lab moving forward. Keep these notes (and the lab steps) handy for future reference
