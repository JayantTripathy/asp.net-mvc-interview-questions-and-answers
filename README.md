# ASP.NET MVC Interview Questions & Answers

> Click :star:if you like the project. Follow me [@JayantT](https://www.youtube.com/jayantT/) for technical videos.


### Table of Contents

### Table of Contents

| No. | Questions |
|---- | ---------
|1 | [What is MVC?](#What-is-MVC-(Model-view-controller)?)|
|2 | [What are the advantages of MVC?](#what-are-the-advantages-of-mvc)|
|3 | [Explain MVC design pattern?](#Explain-MVC-design-pattern?)|

1. ### What-is-MVC-(Model-view-controller)?

Model–view–controller (MVC) is a software architectural pattern for implementing user interfaces. It divides a given software application into three interconnected parts, so as to separate the internal representation of information from the way that information is presented to or accepted by the user.

The ASP.NET MVC framework provides an alternative to the ASP.NET Web Forms pattern for creating web applications. The ASP.NET MVC Framework is a lightweight, highly testable presentation framework that (as with Web Forms-based applications) is integrated with existing ASP.NET features, such as master pages and membership-based authentications. The MVC framework is defined in the System.Web.Mvc assembly. It provides full control over HTML, JavaScript and CSS. It's the better as well as a recommended approach for large-scale applications where various teams are working together.

The MVC model also provides full control over HTML, CSS, and JavaScript.

The MVC model defines web applications with 3 logic layers:

•	The business layer (Model logic)

•	The display layer (View logic)

•	The input control (Controller logic)

  **[⬆ Back to Top](#table-of-contents)**

2. ### What are the advantages of MVC?
**Multiple view support** - Due to the separation of the model from the view, the user interface can display multiple views of the same data at the same time.

**Change Accommodation** - User interfaces tend to change more frequently than business rules (different colors, fonts, screen layouts, and levels of support for new devices such as cell phones or PDAs) because the model does not depend on the views, adding new a type of views to the system generally does not affect the model. As a result, the scope of change is confined to the view.

**SoC** – Separation of Concerns - Separation of Concerns is one of the core advantages of ASP.NET MVC. The MVC framework provides a clean separation of the UI, Business Logic, Model or Data.

**More Control** - The ASP.NET MVC framework provides more control over HTML, JavaScript and CSS than the traditional Web Forms.

**Testability** - ASP.NET MVC framework provides better testability of the Web Application and good support for the test-driven development too.

**Lightweight** - ASP.NET MVC framework doesn’t use View State and thus reduces the bandwidth of the requests to an extent. Full features of ASP.NET - One of the key advantages of using ASP.NET MVC is that it is built on top of ASP.NET framework and hence most of the features of the ASP.NET like membership providers, roles, etc can still be used.

  **[⬆ Back to Top](#table-of-contents)**

3. ### Explain MVC design pattern?

MVC design pattern splits an application into three main aspects: Model, View, and Controller
**Model** - The Model represents a set of classes that describe the business logic i.e. business model as well as data
access operations i.e. data model. It also defines business rules for data, which means how the data can be changed and 
manipulated.
**View** - The View represents the UI components like CSS, jQuery, HTML, etc. It is only responsible for displaying the 
data that is received from the controller as a result. This also transforms the model(s) into UI.
**Controller** - The Controller is responsible for processing incoming requests. It receives input from users via the View,
then processes the user's data with the help of the Model and passes the results back to the View. Typically, it acts as 
the coordinator between the View and the Model

  **[⬆ Back to Top](#table-of-contents)**

