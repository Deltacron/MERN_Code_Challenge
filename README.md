# MERN Code Challenge 

Your tasks is to create a small Star wars Fan Website.

# Apis: https://swapi.dev
Click on the Documentation in the upper right corner. In the documentation, please find the panel with Resources in the left side and utilize that to create the application.

# Task
You need to create a server in NodeJs will fetch data from swapi.dev and send it to your frontend website. The Front-end website needs to be developed using ReactJs. Except for the login endpoint, rest of the endpoints will need to access through the token that is returned after a successful login.

# Steps
Write a React app that utilize apis from your NodeJs server.
<ul>
  <li>First of all show login page to ask the user for credentials. Once the user is validated, return a token from your NodeJs server which will be used for rest of the api calls to your server.</li>
	<li>Use redux / context api for state management and Axios (or similar library) for fetching data from APIs.</li>
	<li>Utilize the apis and create Home page with at least three categories/resources i.e People, Starships and Planets (follow the instructions give under api to find out resource panel on swap.dev). </li>
	<li>When user clicks on a category, it will navigate to another page with list of subitems in that category.</li>
	<li>Display spinner or placeholder component while the API request is ongoing.</li>
	<li>Make it look decent and somewhat responsive so that it doesn’t look terrible on a mobile phone.</li>
  <li>Add images for each category and sub-items. Fetch the images from NodeJs server and DO NOT add them on the frontend.</li>
	<li>Push the code to a public github repo wilth a README.md that explains how to execute the app.</li>
  <li>Deploy the app onto heroku server</li>
</ul>

# BONUS
	•	Dockerize the app.
	•	Write realistic unit/end-to-end tests.
