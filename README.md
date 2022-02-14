# MERN Code Challenge 
Your task is to create a small Star wars Fan Website.

# APIs: https://swapi.dev/documentation
In the documentation, please find the menu panel titled with Resources on the left-hand side and utilize that to create the application.

# Task
You need to create a server in NodeJs will fetch data from swapi.dev and send it to your frontend website. The Front-end website needs to be developed using ReactJs. Except for the login endpoint, the rest of the endpoints will need to access through the token that is returned after a successful login.

## Steps
Write a React app that utilizes APIs from your NodeJs server.
<ol>
  <li>First of all, show the login page to ask the user for credentials. Once the user is validated, return a token from your NodeJs server which will be used for the rest of the API calls to your server.</li>
	<li>Use redux / context API for state management and Axios (or similar library) for fetching data from APIs.</li>
	<li>Utilize the APIs and create a Home page with at least three categories/resources i.e People, Starships, and Planets (follow the instructions given under API to find out resource panel on swap.dev).</li>
	<li>When the user clicks on a category, it will navigate to another page with a list of subitems in that category.</li>
	<li>Display spinner or placeholder component while the API request is ongoing.</li>
	<li>Make it look decent and somewhat responsive so that it doesn’t look terrible on a mobile phone.</li>
  	<li>Add images for each category and sub-items. Fetch the images from the NodeJs server and DO NOT add them on the frontend.</li>
	<li>Push the code to a public GitHub repo with a `README.md` that explains how to execute the app.</li>
  	<li>Deploy the app onto a Heroku, AWS instance, or equivalent.</li>
</ol>

## Bonus🌟
<ol>
<li>Dockerize the app.</li>
<li>Write realistic unit/end-to-end tests.</li>
</ol>
