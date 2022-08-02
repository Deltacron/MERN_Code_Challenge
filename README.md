# MERN Code Challenge 
Your task is to create a small Star wars Fan Website.

# APIs: https://swapi.dev/documentation
In the documentation, please find the menu panel titled with Resources on the left-hand side and utilize that to create the application.

# Task
You need to create a server in NodeJs will fetch data from swapi.dev and send it to your frontend website. The Front-end website needs to be developed using ReactJs. Except for the login endpoint, the rest of the endpoints will need to access through the token that is returned after a successful login.

## Steps
Write a React app(with proper folders) that utilizes APIs from your NodeJs server.
<ol>
  <li>First of all, show the login page to ask the user for credentials. Once the user is validated, return a token from your NodeJs server which will be used for the rest of the API calls to your server.</li>
	<li>Use redux for state management and Axios (or similar library) for fetching data from APIs.</li>
	<li>Create a Login page and validate the user using the api created in the step 1.</li>
	<li>Utilize the APIs and create a Home page with at least three categories/resources i.e People, Starships, and Planets (follow the instructions given under API to find out resource panel on swap.dev).</li>
	<li>When the user clicks on a category, it will navigate to another page/panel which shows subitems in that category.</li>
	<li>Display spinner/loader or placeholder component while the API request is ongoing.</li>
	<li>Create a really elegant, good looking and responsive application that adopts to different screen resolutions. DO NOT submit the test with basic design else your test will be rejected immediately.</li>
	<li>Write your own css to design the pages. DO NOT use any third party library for CSS. 
  	<li>Add images for each category and sub-items. Fetch the images from the NodeJs server and DO NOT add them on the frontend. You will fail the test if you did not add images or if the images are fetched locally.</li>
	<li>Push the code to a public GitHub repo with a `README.md` that explains how to execute the app.</li>
  	<li>Deploy the app onto a Heroku, AWS instance, or equivalent.</li>
</ol>

As a sample, you can refer to https://www.starwars.com/films.

## Warnings
<ol>
	<li>Without images, you will fail the test immediately.</li>
	<li>Focus on good coding practices. </li>
	<li>Code quality needs to be good. Bad code quality might get rejected immediately.</li>
</ol>

## Bonus🌟
<ol>
	<li>Create as many reusable components as you can.</li>
<li>Dockerize the app.</li>
<li>Write realistic unit/end-to-end tests.</li>
</ol>
