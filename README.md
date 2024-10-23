# ASP.NET MVC Interview Questions & Answers

> Click :star:if you like the project. Follow me [@JayantT](https://www.youtube.com/jayantT/) for technical videos.


### Table of Contents

| No. | Questions |
|---- | ---------
|1 | [What is MVC?](#What-is-MVC-(Model-view-controller)?)|
[](#)

### ASP.NET MVC

1. ### What is MVC (Model view controller)?

Model–view–controller (MVC) is a software architectural pattern for implementing user interfaces. It divides a given software application into three interconnected parts, to separate the internal representation of information from the way that information is presented to or accepted from the user.

The ASP.NET MVC framework provides an alternative to the ASP.NET Web Forms pattern for creating web applications. The ASP.NET MVC Framework is a lightweight, highly testable presentation framework that (as with Web Forms-based applications) is integrated with existing ASP.NET features, such as master pages and membership-based authentications. The MVC framework is defined in the System.Web.Mvc assembly. It provides full control over HTML, JavaScript and CSS. It's the better as well as a recommended approach for large-scale applications where various teams are working together.

MVC is a framework for building web applications using a MVC (Model View Controller) design:

•	The Model represents the application core (for instance a list of database records).

•	The View displays the data (the database records).

•	The Controller handles the input (to the database records).


The MVC model also provides full control over HTML, CSS, and JavaScript.

The MVC model defines web applications with 3 logic layers:

•	The business layer (Model logic)

•	The display layer (View logic)

•	The input control (Controller logic)

The Model is the part of the application that handles the logic for the application data. Often model objects retrieve data (and store data) from a database.

The View is the part of the application that handles the display of the data. Most often the views are created from the model data.
The Controller is the part of the application that handles user interaction. Typically controllers read data from a view, control user input, and send input data to the model.

The MVC separation helps you manage complex applications, because you can focus on one aspect a time. For example, you can focus on the view without depending on the business logic. It also makes it easier to test an application.


  **[⬆ Back to Top](#table-of-contents)**

