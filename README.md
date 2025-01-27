
# NodeJS Project Criteria

In this NodeJS project,you’ll build an application to display user’s posts, posts’ comments along with location of the user.
This application only uses HTML + js + CSS files.
# Activity on this project include the below:

	•	Github activities
	•	Fork A repository from https://github.com/bellaxing/cs445-project.git
	•	Clone a repository to your local
	•	Create a feature branch, and commits all changes you made for this project
	•	Create a pull request to https://github.com/bellaxing/cs445-project.git
	•	After you finish everything, also create a github pages to host your project.  Make sure all features are committed.


# User’s POSTs SPA

Make use of the JSON service http://jsonplaceholder.typicode.com. Write a SPA page that processes this simulated JSON blog data. 

	• Create a Single Page Application (SPA) with an input form to take a userId from the browser
	• Display user name, email, address, current location and all posts belonging to this userId
	• Display user’s name, email and address
	• Display current location for the user (use latitude, longitude)
	• Check this API provider: https://developer.mapquest.com/documentation/geocoding-api/reverse/get/. You may pass an API key, try to register on the website
	• retrieve all posts from selected user /posts?userId=1. For efficiency remember to attach entire lists to DOM rather than each list item
	• For every post, include a button (show comments), upon clicking the button show all comments for the specific post. (optional)
	• retrieve all comments from selected post /comments?postId=1
	• Hint: hide postId in data- attribute in each post.

Note: You may need to use $(DOM).on() to attach event handler with functions to newly created elements

