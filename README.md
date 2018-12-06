## About

Check out the [application on Heroku](https://stats-engagement.herokuapp.com/).
<br/>

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app). 
The front-end is a React application, with Node and Express for the backend. 

The db is set up with `games`, `tokens`, `questions`, and an intermediary table called 
`question_tokens` containing the "rules" between a question and a token. 

<img src="https://github.com/antoniablair/stats-engagement/blob/master/client/src/images/screenshot.png" width="500">

###  Admin

I used an open source library called Forest Lumber to generate an admin panel to manage this project. 

The admin panel code is stored in a [different github repo]('https://github.com/antoniablair/stats-engagement-admin'), mainly to make it easier for me to deploy to Heroku.


### ToDos:
- Spend more time on the design and layout, especially for smaller devices
- Make it so that the game's questions are asked in random orders and that some questions can be repeating
- I used bars for the token levels since it reminded me the most of an RPG, 
but ideally those should be updated to have different colors, and actually display 0-5 nodes
- Save the user's progress in localStorage so they can resume the game later
- Add type checking
- Surface any API errors to the user
