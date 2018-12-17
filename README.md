# E2E tests for DataCast UI

This repository contains automated E2E test cases for DataCast web UI using [Nightwatch] (http://nightwatchjs.org)

Clone this repository to test the DataCast web UI  e2e tests

```
git clone https://github.com/LiaisonTechnologies/lens-nightwatch-tests.git
```

## Description

Purpose of this repository is to test the automated e2e test cases for DataCast web UI. Providing most of the set up ready configured and as easy as by running `git clone` and `npm install`.


**Note:** Running `npm install` downloads Nightwatch.js, Selenium standalone server, Chromedriver, IE driver and Gecko driver (Firefox) automatically. No extra setup needed.


## Prerequisites

* [NodeJS](https://nodejs.org/en/) - for Nightwatch
* [Java Runtime](http://www.oracle.com/technetwork/java/javase/downloads/index.html) - for Selenium standalone server


## Usage

* Install dependencies

  ```
  npm install
  ``` 

* Run tests

  ```
  # Test against default environment (Firefox)
  npm test 

  # Test against all environments (Firefox, Chrome and IE- right now this is not working)
  npm run test:all 
  ``` 
  
## Writing tests

Refer to: `http://nightwatchjs.org/guide`.

## Contributing
 
Fork this repository and send a pull request containing the improvements to the maintainer.