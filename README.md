# Chitter-Chatter
A messaging app that plays sounds and animations with every message.    

## Features
Users are able to send and recieve messages with other users. When a user types a letter on the site, a sound and animation will play. Users can replay the sounds and animations that play when other users send them messages. Users are also able to edit their information.  

## Demo
[Live](https://chitterchatter.netlify.com)(Login:test)| [Video](https://youtu.be/LXnu3VkGr04)

## Built with
 *Back-end*
- [Ruby on Rails](https://rubyonrails.org) - Server Framework
- [PostgreSQL](https://www.postgresql.org) - Database

*Front-end*
- Vanilla HTML, Custom CSS for styling
- [webpack](https://webpack.js.org) - Script and Asset bundler
- [Paper.js](http://paperjs.org/) - Vector Graphics Scripting Library
- [howler.js](https://howlerjs.com) - JavaScript Audio Library


## Installation
*Requirements*
 - [Node.js](https://nodejs.org/en/)
 - [Installing Ruby](https://www.ruby-lang.org/en/documentation/installation/)
 - [PostgreSQL](https://www.postgresql.org)


In your clone/fork of this repo: 
```bash
npm install - #installs all dependencies
npm run start - #opens webpack dev server - will refresh upon changes in JS
npm run build - #compiles final product and pushes to dist folder
```

The instructions for the back-end of this app are [here](https://github.com/Giagnus64/Chitter-Chatter-API). You'll need to clone/fork both repos and change your fetch URLS if you want to change the API. Otherwise, the app will make calls to the API hosted on heroku. 


## License
[MIT](https://choosealicense.com/licenses/mit/)
