# Class 26: Intro to Django

## What are the key components of the Django framework, and how do they contribute to building a web application?

the key components of Django are:

- Model: which is the data layer, it is the database that contains the data that the user will interact with.
- View: which is the logic layer, it is the layer that contains the logic of the application, and it is the layer that connects the model and the template.
- Template: which is the presentation layer, it is the layer that contains the HTML files that will be rendered to the user.

it contributes to building a web application by providing a framework that contains all the needed components to build a web application, and it provides a way to connect these components together.

## Explain the role of Django’s MTV (Model-View-Template) architecture and how it handles a typical web request-response cycle

Django’s MTV (Model-View-Template) architecture is a software design pattern for developing a web application, it's role is to separate the logic of the application from the presentation of the application.

it handles a typical web request-response cycle by:

- The user requests a page by entering a URL in the browser.
- Django receives the request and passes it to the URL dispatcher.
- The URL dispatcher sends the request to the view.
- The view processes the request and returns a response.
- The response is sent back to the user.

## What is the purpose of Tailwind CSS, and how does it differ from Bootstrap CSS?

Tailwind CSS is a utility-first CSS framework, it is a framework that provides a set of utility classes that can be used to style the HTML elements, it is help in building responsive websites without writing any CSS code.