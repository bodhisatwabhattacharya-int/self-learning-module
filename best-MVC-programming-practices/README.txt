Best MVC Programming Practices
------------------------------

Model View Controller or MVC as it is popularly called, is a software design pattern for developing web applications. A Model View Controller pattern is made up of the following three parts:

	* Model - The lowest level of the pattern which is responsible for maintaining data.

	* View - This is responsible for displaying all or a portion of the data to the user.

	* Controller - Software Code that controls the interactions between the Model and View.

MVC is popular as it isolates the application logic from the user interface layer and supports separation of concerns. Here the Controller receives all requests for the application and then works with the Model to prepare any data needed by the View. The View then uses the data prepared by the Controller to generate a final presentable response. The MVC abstraction can be graphically represented as follows.

	* The model
	  The model is responsible for managing the data of the application. It responds to the request from the view and it also responds to instructions from the controller to update itself.

	* The view
	  A presentation of data in a particular format, triggered by a controller's decision to present the data. They are script based templating systems like JSP, ASP, PHP and very easy to integrate with AJAX technology.

	* The controller
	  The controller is responsible for responding to user input and perform interactions on the data model objects. The controller receives the input, it validates the input and then performs the business operation that modifies the state of the data model.


SOME MORE RESOURCES
-------------------

	* http://www.yiiframework.com/doc/guide/1.1/en/basics.best-practices
	* https://r.je/ [Tom Butler's Programming Blog. MVC, PHP, Best practices]

