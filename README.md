# DocSafeTask

This is a user login and registration app using AngularJS, Javascript, HTML, CSS, Bootstrap, Node.js, Express, Passport and Mongoose.

I did setup modules, middleware and create a Bootstrap lauout.

Steps:
I created the package.json file and installed some dependancies which is used in this application.

I created a Node server to run project and I used Express Js to create the server.

I created the app.js file:
	-Init app
	-View engine
	-Body-parser Middleware
	-Set static folder
	-Express session
	-Passport init
	-Express validator
	-Connect Flash
	-Global Variables
	-Set port

I connected the app to mongoose.

I created the routes folder. Created the 2 js files inside routes folder: 
	1.index.js
	2.user.js
I created the views folder. Inside views folder:
	1.layouts folder
		-layout.handlebars
	2.index.handlebars
	3.login.handlebars
	4.register.handlebars

I created the public folder. Inside the public folder:
	1.css: style.css file and bootstrap.css file(put the file from getbootstrap.com)
	2.fonts (put the folder from getbootstrap.com)
	3.js (put the folder from getbootstrap.com)

I did coding for validation of ragistration and login form.

I created models folder.
	1.user.js : I did coding of mongoose for registration an dlogin form.

In this application, I created the functionality for the registration form using Passport.
I did also encrypt/hash passwords using bcrypt.

I added the login functionality using Passport along with a local strategy. I implemented access control.

Version 1.0.0

