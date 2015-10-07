A. What server framework did you choose and why?
Ans. I have chosen Node.js to design this application. Node.js has built in support for package management using the NPM (Node Package Manager) tool that provides you with few handy modules such as express, connect, etc. Node.js is best fit for exposing the data from object DBs (e.g. Mongo DB) because JSON stored data allow it to function without the impedance mismatch and data conversion.
B. What client framework did you choose and why?
Ans. I have used JQuery as a client framework because of the following reasons:
1)	It is very easy to use
2)	It has a vast set of library.
3)	Ajax Support: This is very handy, especially for this project as the goal of the project was to display data dynamically. 

C. What aspect of the implementation did you find easy, if any, and why?
Ans. Server Side.  Nodejs’s express module made a lot of my job easier to implement. Also, there is less work as compared to the client side where you also need to take care of HTML elements and their look and feel.

D. What aspect of the implementation did you find hard, if any, and why?
Ans. Client Side. Again, because of the extra overhead to display HTML elements in correct format and also making sure of the correct AJAX calls that binds the data. 

E. What components OTHER than your client and server framework did you install, if any, and if so, what is their purpose for your solution?
Ans. 	1: Bootstrap: For designing and implementing the client side.
	2: Google Map API:  For implementing Google maps.
	3: Git Bash: Command Line utility to upload project into the GitHub.
	4: Heroku toolbelt:  For deployment of project and running the server. 

F. What Ubuntu commands are required to deploy and run your server?
Ans. Below commands are used to deploy and run the server:
	1: heroku login
	2: git clone https://github.com/ ankitaduggal /cse5335-project-1
	3: cd cse5335-project-1
	4: heroku create cse5335-1001047271
	5: git push heroku master
	6: heroku open
