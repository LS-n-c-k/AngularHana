![Standard Rev 90](textImgs/capture2.png)

<h1><font color="orange"> Angular- with Odata service </font></h1>
---------------------------------------------------------------------------
We are declaring our table rows inside **<tr>** tag.

We will use **$http** to consume the odata service in AngularJS app.

Here we are using **ng-Repeat** directive to instantiates our template once per our row items from a collection of rows in our table.

Each repetition has access to the current repetition object.
- **$http** is an AngularJS service for reading data from remote servers
- **AngularJS $http** service makes a request to the server, and returns a response
- The $http service is a core Angular service that facilitates communication with the remote HTTP servers via the browser's  XMLHttpRequest object
-  **$scope** object is used by AngularJS to invoke the controller in the script. 
-  In AngularJS **$scope** is used to declare application variable and function.
-  Then Creating **myData** property in scope and binding the result of the table to the property declare in the scope

1.Call the odata service using $http

![Standard Rev 90](textImgs/19.1.png)

- A view of AngularJS code
![Standard Rev 90](textImgs/20.png)

2.Output
- We are getting the output from the oData service
in our table as the rows we have given as
**Product Id**,**Category**,**Price**,**Dimension**


![Standard Rev 90](textImgs/normalout.png)

The output what we are getting is not having a good look and feel, so in the next step we will use **Bootstrap** to make good look and feel for the output


3.Use **Bootstrap**

- Bootstrap is the most popular HTML, CSS, and JavaScript framework for developing responsive, mobile-first web sites
- Bootstrap makes front-end web development faster and easier
- It's made for folks of all skill levels, devices of all shapes, and projects of all sizes
- Bootstrap easily and efficiently scales your websites and applications with a single code base, from phones to tablets to desktops with CSS media queries
- With Bootstrap, you get extensive and beautiful documentation for common HTML elements, dozens of custom HTML and CSS components, and awesome jQuery plugins
- Bootstrap is open source. It's hosted, developed, and maintained on GitHub
- Millions of amazing sites across the web are being built with Bootstrap

![Standard Rev 90](textImgs/21.png)

4.Output

![Standard Rev 90](textImgs/BootStrap.png)


- After using Bootstrap the table's look and feel become good. 
