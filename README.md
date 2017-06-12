## Synopsis

Who likes quizzes?

...

If you read this far, then the answer is you and you are correct! This is a coding sample created to demonstrate technical, organizational, and creative aptitude for an established leader in the realm of all things factual.

This webapp was written using React.js.

## Requirements

1. Node.js

## How to setup

1. Extract files
2. Open node command line and browse to directory location
3. Install app (npm install)
4. Run app (npm start)

## Comments 

This was a lot of fun and really enjoyed playing with the transitions. It did not seem necessary to use a comprehensive state management store at first, but then saw a variety of ways this could be further expanded and in retrospect, I would have used redux.

The getData method could have been wired up to pass in dynamic parameters but it did not seem clear of how to correlate getting question data from the quiz data when parsing through the json, so it exists as an extendable method to vary on startup.

The quiz does use forEach with the answers, so it should work with any type of multiple choice quiz and not just TRUE_FALSE.

I ran into some issues parsing the single quote tick from the json files and will do some more research and how to properly decode the json text.

## UX Thoughts

+ I used the react-starter pack to initialize the project with hot loader to update both js and css. This also explains the spinning react logo which I enjoyed enough to keep in the app.

+ Sorry, not sorry for using "cursive" (which defaults to ComicSans in Windows). It seemed appropriate for a "comics" quiz and was told to have fun, so I did just that.

+ I fell in love with the idea of the 3d revealing buttons and thought it came out well. It has kind of a Family Feud feel to it.

+ The results page still feels raw and underdeveloped from a design perspective. Some type of striped CSS or line-breaks might provide better separation. 

+ I think gamification brings a better experience, and a cooler scoring badge design would have been an enhancement. I envision a grander scope of collecting these badges and filling up a vairtual "trophy case" of other completed quizzes grouped by categories, which would ideally lead towards other related quizzes. 

# TODO

- Timer
- Go back and set Document title and Meta keywords in either the App component constructor or componentDidMount method.
- Animate loading of each result on result page. I imagine a casacading tiled fadein effect. I would also implement a 3d spinning transition for the token.
