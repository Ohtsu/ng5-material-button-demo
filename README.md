
# _ng5-material-button-demo_ Angular5 initial project installed with libraries which are needed for Angular Material
[![MIT License](http://img.shields.io/badge/license-MIT-blue.svg?style=flat)](LICENSE)


_ng5-material-button-demo_ is an Angular5 initial project for programmers who want to start up Angular Material easily.

_Video Explanation_
<https://youtu.be/ttLh47qv9pk>

_Full Source Code_
<https://github.com/Ohtsu/ng5-material-button-demo>

## Overview 
    
At first, please refer to "Angular Material Getting started" page as follows. 
    
<https://material.angular.io/guide/getting-started>
 
This project is based on the steps explained in the page. 

The following "Step" number is based on the page. But the step 3 is not included because module names depend on the modules which you want to include.

### Installed Libraries and Settings 

   - @angular/material (Step 1)

   - @angular/cdk (Step1)

   - @angular/animations (including the modification of 'src/app/app.module.ts' file) (Step2)

   - Add default theme(indigo.pink.css) to styles.css file (step4)

   - hammerjs (including the modification of 'src/main.ts' file (step5)

   - Add the official Material Design Icons (modification of 'index.html' file) (Step6) 


 Of course, you can change the structure by modifying the following _Package.json_ file.

```bash

  "dependencies": {
    "@angular/animations": "^5.0.1",
    "@angular/cdk": "^5.0.0-rc0",
    "@angular/common": "^5.0.0",
    "@angular/compiler": "^5.0.0",
    "@angular/core": "^5.0.0",
    "@angular/forms": "^5.0.0",
    "@angular/http": "^5.0.0",
    "@angular/material": "^5.0.0-rc0",
    "@angular/platform-browser": "^5.0.0",
    "@angular/platform-browser-dynamic": "^5.0.0",
    "@angular/router": "^5.0.0",
    "core-js": "^2.4.1",
    "gulp": "^3.9.1",
    "hammerjs": "^2.0.8",
    "rxjs": "^5.5.2",
    "zone.js": "^0.8.14"
  },
  "devDependencies": {
    "@angular/cli": "1.5.0",
    "@angular/compiler-cli": "^5.0.0",
    "@angular/language-service": "^5.0.0",
    "@types/jasmine": "~2.5.53",
    "@types/jasminewd2": "~2.0.2",
    "@types/node": "~6.0.60",
    "codelyzer": "~3.2.0",
    "jasmine-core": "~2.6.2",
    "jasmine-spec-reporter": "~4.1.0",
    "karma": "~1.7.0",
    "karma-chrome-launcher": "~2.1.1",
    "karma-cli": "~1.0.1",
    "karma-coverage-istanbul-reporter": "^1.2.1",
    "karma-jasmine": "~1.1.0",
    "karma-jasmine-html-reporter": "^0.2.2",
    "protractor": "~5.1.2",
    "ts-node": "~3.2.0",
    "tslint": "~5.7.0",
    "typescript": "~2.4.2"
  }


```

## Prerequisite

   - Git
   - Node.js
   - TypeScript2
   - Angular5
   - Angular/cli



## Installation

To install this program:

   - Make your own directory and change into it.

```bash
$ mkdir mydir
$ cd mydir
```
   - Make the clone as follows.

```bash
$ git clone https://github.com/Ohtsu/ng5-material-button-demo.git
```

   - Change into _ng5-material-button-demo_ and run "npm install".

```bash
$ cd ng5-material-button-demo
$ npm install 
```


#### Check Your Program

If you start local server as follows, you can get the first page in your browser by accessing **http://localhost:4200**.


```bash
$ ng serve
```

  - ***First Page*** 

  <img src="https://raw.githubusercontent.com/Ohtsu/images/master/ng5-i18n-demo/ng5-i18n-demo_en-page_01.png" width= "640" >


#### Stop Local Server

Input **Ctrl+C** and **y+Return** to stop the local server.




## Version

   - ng5-material-button-demo : 0.1
   - Angular5     : 5.0.0
   - @angular/cdk : 5.0.0-rc0
   - @angular/material : 5.0.0-rc0,
   - hammerjs : 2.0.8
   - @angular/cli : 1.5.0



## Reference

- "Agular Material Getting started",
<https://material.angular.io/guide/getting-started>



## Change Log

 - 2017.11.15  version 0.1.1 uploaded


## Copyright

copyright 2017 by Shuichi Ohtsu (DigiPub Japan)


## License

MIT © [Shuichi Ohtsu](ohtsu@digipub-net.com)
