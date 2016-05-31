![Standard Rev 90](C:/Users/Admin/Desktop/textImgs2/capture2.png)

<h1><font color="orange">Create XS project for AngularJS app</font></h1>
---------------------------------------------------------------------------

1.Create **XS project**

- Switch to ‘project explorer’. Go to File -> New -> Project -> "**XS Project** -> Give the project name (In our example it's AngularJS)

![Standard Rev 90](C:/Users/Admin/Desktop/textImgs2/7.png)

2.Create .xsapp 

- Right click on your XS project(AngularJS) and create a new file call ".xsapp".

![Standard Rev 90](C:/Users/Admin/Desktop/textImgs2/8.png)

3.Create .xsaccess– copy the file content

- Right click on your XS project(AngularJS) and create a new file call “.xsaccess”

![Standard Rev 90](C:/Users/Admin/Desktop/textImgs2/9.png)

- Share the project with the HANA system

![Standard Rev 90](C:/Users/Admin/Desktop/textImgs2/10.png)


4.service.xsodata - copy the file content 

- Right click on your XS project(AngularJS) and create a new file call “service.xsodata” and click **finish**

![Standard Rev 90](C:/Users/Admin/Desktop/textImgs2/14.png)

- Here we're creating odata service on the Product table from TUTORIAL schema(Which we created in first tutorial)

![Standard Rev 90](C:/Users/Admin/Desktop/textImgs2/15.png)

- Activate all the files present in your xs project(AngularJS)

![Standard Rev 90](C:/Users/Admin/Desktop/textImgs2/16.png)

- Test the odata service on browser

![Standard Rev 90](C:/Users/Admin/Desktop/textImgs2/18.png)


5.create index.html for AngulerJs app 

- Right click on your XS project(AngularJS) and create a new file call “index.html” and click **finish**

![Standard Rev 90](C:/Users/Admin/Desktop/textImgs2/12.png)

<h3>Main parts of AngularJS app</h3>

- Add ng-app="myApp" in html tag
- Use "http://ajax.googleapis.com/ajax/libs/angularjs/1.4.8/angular.min.js" on head
- Add ng-controller="productsCtrl" to div tag(where we want get data from the JS script)
- In script create a Angular Js app "var app = angular.module('myApp', [ ]);"
- write the actual code in "app.controller"

![Standard Rev 90](C:/Users/Admin/Desktop/textImgs2/13.png)



In the next tutorial we'll consume the odata service in Angular app






