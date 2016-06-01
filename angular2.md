![Standard Rev 90](textImgs/capture2.png)

<h1><font color="orange">Create XS project for AngularJS app</font></h1>
---------------------------------------------------------------------------

1.Create **XS project**

- Switch to ‘project explorer’. Go to File -> New -> Project -> "**XS Project** -> Give the project name (In our example it's AngularJS)

![Standard Rev 90](textImgs/7.png)

2.Create .xsapp 

- Right click on your XS project(AngularJS) and create a new file call ".xsapp".

![Standard Rev 90](textImgs/8.png)

3.Create .xsaccess– copy the file content

- Right click on your XS project(AngularJS) and create a new file call “.xsaccess”

![Standard Rev 90](textImgs/9.png)

- Share the project with the HANA system

![Standard Rev 90](textImgs/10.png)


4.service.xsodata - copy the file content 

- Right click on your XS project(AngularJS) and create a new file call “service.xsodata” and click **finish**

![Standard Rev 90](textImgs/14.png)

- Here we're creating odata service on the Product table from TUTORIAL schema(Which we created in first tutorial)

![Standard Rev 90](textImgs/15.png)

- Activate all the files present in your xs project(AngularJS)

![Standard Rev 90](textImgs/16.png)

- Test the odata service on browser

![Standard Rev 90](textImgs/18.png)


5.create index.html for AngulerJs app 

- Right click on your XS project(AngularJS) and create a new file call “index.html” and click **finish**

![Standard Rev 90](textImgs/12.png)

<h3>Main parts of AngularJS app</h3>

- To define AngularJs application in our Angular App we are going to define ng-app="myApp" in html tag
- AngularJS is distributed as a JavaScript file and we can define AngularJS to a web page with a script tag:      "http://ajax.googleapis.com/ajax/libs/angularjs/1.4.8/angular.min.js" on head
- Now we need to define Application Controller to our code by the tag: ng-controller="productsCtrl" to div tag(where we want to get data from the JS script).Controller is created by Javascript ObjectConstructor,it is a JavaScript Object.
- In script create a Angular Js app "var app = angular.module('myApp', [ ]);",this application will run under <div> of our script
- Now we need to write  the actual code in "app.controller"
- Here 'productsCtrl' function is a javascript function.

![Standard Rev 90](textImgs/13.png)



In the next tutorial we'll consume the oData Service in Angular app to show the datas in our Angular app






