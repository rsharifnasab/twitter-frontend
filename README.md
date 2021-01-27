# Twitter-clone Front-end

build twitter-like front-end for internet engeering course - fall 99

with react+redux

inspired by [real word react-redux ](https://github.com/gothinkster/react-redux-realworld-example-app) project

## team mates

1. Roozbeh Sharifnasab [+](github.com/rsharifnasab)
2. Parsa Fadaee [+](github.com/ParsaFadaei)
3. Seyed Mohammad Farahani [+](github.com/SeyedMohammadFarahani)

## Special thanks to

-   Course instructor: Parham Alvani [+](github.com/1995parham)
-   Teaching assistant team
    1. Mohammad Movahed [+](https://github.com/funnyphantom)
    2. Reza Ferdowsi [+](https://github.com/rferdosi)
    3. Parsa Hejabi [+](https://github.com/ParsaHejabi)
    4. Pouya [+]()

## Getting started

To get the frontend running locally:

-   Clone this repo
-   install `cross-env`
-   `npm install` to install all req'd dependencies
-   `npm start` to start the local server (this project uses create-react-app)

Local web server will use port 4100. You can configure port in scripts section of `package.json`: we use [cross-env](https://github.com/kentcdodds/cross-env) to set environment variable PORT for React scripts, this is Windows-compatible way of setting environment variables.


### Making requests to the backend API
If you want to change the API URL to a local server, simply edit `src/agent.js` and change `API_ROOT` to the local server's URL (i.e. `https://conduit.productionready.io/api`)


#### inspired by [real world](https://github.com/gothinkster/react-redux-realworld-example-app)
