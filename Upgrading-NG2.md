DO a hbrid angular application : run both NG1 (JS) and NG2-4

i follow steps here  :
https://angular.io/docs/ts/latest/guide/upgrade.html
§ PhoneCat Upgrade Tutorial
I clone the phonecat tuto form angular.io
https://github.com/angular/angular-phonecat

then 
https://angular.io/docs/ts/latest/guide/upgrade.html#!#installing-angular
I clone and install NG2 quickstart application
https://angular.io/docs/ts/latest/guide/setup.html
https://angular.io/docs/ts/latest/guide/setup.html#clone

https://github.com/angular/quickstart/archive/master.zip
I copy from quickstart /.../package.json the parts of angular4 dependecies ( all dependencies part)
to phonecat/.../package.json
I copy systemjs.config.js from quickstart to phonecat projects
I

thenI follow all steps including §Bootstrapping a hybrid Phonecat before §Upgrading the Phone service
=> I get errors : see log file

I get some 'mistake'
§creation App Module : 
Creating the AppModule
Now create the root NgModule class called AppModule. There is already a file named app.module.ts (js) that holds the AngularJS module. 
Rename it to app.module.ajs.ts(js) and update the corresponding script name in the index.html as well. 

§Bootstrapping a hybrid Phonecat
So, remove the ng-app attribute from index.html, and instead bootstrap via src/main.ts. #eheb :(either in root dir or app dir)
This file has been configured as the application entrypoint in systemjs.config.js, so it is already being loaded by the browser.
I put main.ts in the root dir with systemjs.config.js
But i am not sure !!

How to get support form google NG2 ? or elsewhere ?
