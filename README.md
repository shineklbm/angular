# AngularJS Folder Structure
app/
----- shared/   // acts as reusable components or partials of our site
---------- sidebar/
--------------- sidebarDirective.js
--------------- sidebarView.html
---------- article/
--------------- articleDirective.js
--------------- articleView.html
----- components/   // each component is treated as a mini Angular app
---------- module1/
--------------- homeController.js
--------------- homeService.js
--------------- homeView.html
---------- module2/
--------------- blogController.js
--------------- blogService.js
--------------- blogView.html
----- data
--------------- module1
---------------------data.json
--------------- module2
---------------------data.json
----- app.module.js
----- app.routes.js
assets/
----- img/      // Images and icons for your app
----- css/      // All styles and style related files (SCSS or LESS files)
----- js/       // JavaScript files written for your app that are not for angular
----- libs/     // Third-party libraries such as jQuery, Moment, Underscore, etc.
index.html

Reference : https://scotch.io/tutorials/angularjs-best-practices-directory-structure
