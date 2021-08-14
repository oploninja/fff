# - <p align="center"><strong><b> OPLO-CONNECT-AUTOMATION-TEST-</b></strong></p>

<p align="center">
  <img src="https://i.giphy.com/media/gw3IWyGkC0rsazTi/giphy.webp" onerror="this.onerror=null;this.src='https://i.giphy.com/gw3IWyGkC0rsazTi.gif';" alt="">
</p>

<p align="center"><i>This repository contains tests for the Oplo Connect platform. It is design to cover functional and visual testing. </i></p>

## Get started

To run the project you will need to:

1. install all dev dependancies from the package.json file:
```
npm install
```

2. place your .env file in the main dir of the project

## Run tests:
* To run your tests from '.tests' folder
```
npm run test 
```

* To run tests with report generated from '.tests' folder
```
npx nightwatch --reporter html-reporter.js 
```

* To run visual regression tests from '.vrt-tests' folder
```
npm run test:vrt
```

* To update the base visuals (consolidate the screenshots)
```
npm run set:vrt
```

## External references 
### Nightwatch.js
#### [Homepage](https://nightwatchjs.org) &bullet; [Getting Started](https://nightwatchjs.org/gettingstarted) &bullet; [Developer Guide](https://nightwatchjs.org/guide) &bullet; [API Reference](https://nightwatchjs.org/api) &bullet; [About](https://nightwatchjs.org/about)

### Mocha and Chai

### Axios


## Project structure
TBA...

![OPLO](https://www.cognizantsoftvision.com/wp-content/uploads/2017/10/05233246/AAEAAQAAAAAAAA0-AAAAJGIwM2QxZTk3LTRmMTItNDU0Ny1hMTYzLWVmY2Q3NzhlYWU0Ng.png "OPLO" )




