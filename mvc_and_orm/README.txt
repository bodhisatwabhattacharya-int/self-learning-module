MVC, Model View and Controller
==============================

Interactions
------------

In addition to dividing the application into three kinds of components, the model–view–controller design defines the interactions between them.

	* A controller can send commands to the model to update the model's state (e.g., editing a document). It can also send commands to its associated view to change the view's presentation of the model (e.g., by scrolling through a document).

	* A model notifies its associated views and controllers when there has been a change in its state. This notification allows the views to produce updated output, and the controllers to change the available set of commands. In some cases an MVC implementation might instead be "passive," so that other components must poll the model for updates rather than being notified.

	* A view requests information from the model that it uses to generate an output representation to the user.

Use in web applications
-----------------------

Although originally developed for desktop computing, model–view–controller has been widely adopted as an architecture for World Wide Web applications in major programming languages. Several commercial and noncommercial application frameworks have been created that enforce the pattern. These frameworks vary in their interpretations, mainly in the way that the MVC responsibilities are divided between the client and server.

Early web MVC frameworks took a thin client approach that placed almost the entire model, view and controller logic on the server. In this approach, the client sends either hyperlink requests or form input to the controller and then receives a complete and updated web page (or other document) from the view; the model exists entirely on the server. As client technologies have matured, frameworks such as JavaScriptMVC and Backbone have been created that allow the MVC components to execute partly on the client (see also AJAX).

MVC is popularly used in web design. An HTML file serves as the model, containing the text to be shown on a webpage, a CSS file contains a description or view of the page's layout, and the browser serves as the controller, rendering the HTML and CSS data as the webpage we read. 

Other Resources
---------------

	1. http://www.sitepoint.com/the-mvc-pattern-and-php-1/
	2. PHP-MVC PROJECT http://www.php-mvc.net/
	3. http://www.phpro.org/tutorials/Model-View-Controller-MVC.html
	4. http://www.udemy.com/blog/php-mvc-tutorial/


ORM, Object-relational mapping
==============================

Overview
--------

In object-oriented programming, data management tasks act on object-oriented objects that are almost always non-scalar values. For example, consider an address book entry that represents a single person along with zero or more phone numbers and zero or more addresses. This could be modeled in an object-oriented implementation by a "Person object" with attributes/fields to hold each data item that the entry comprises: the person's name, a list of phone numbers, and a list of addresses. The list of phone numbers would itself contain "PhoneNumber objects" and so on. The address book entry is treated as a single object by the programming language (it can be referenced by a single variable containing a pointer to the object, for instance). Various methods can be associated with the object, such as a method to return the preferred phone number, the home address, and so on.

However, many popular database products such as structured query language database management systems (SQL DBMS) can only store and manipulate scalar values such as integers and strings organized within tables. The programmer must either convert the object values into groups of simpler values for storage in the database (and convert them back upon retrieval), or only use simple scalar values within the program. Object-relational mapping is used to implement the first approach.

The heart of the problem is translating the logical representation of the objects into an atomized form that is capable of being stored in the database, while preserving the properties of the objects and their relationships so that they can be reloaded as objects when needed. If this storage and retrieval functionality is implemented, the objects are said to be persistent.

Other Resources
---------------

	1. http://propelorm.org/
	2. http://en.wikipedia.org/wiki/Object-relational_mapping
	3. Slideshare http://slidesha.re/1wi6Foa