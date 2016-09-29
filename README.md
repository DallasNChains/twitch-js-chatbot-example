# Twitch Chatbot Hackathon
Welcome to the chatbot hackathon! We’re looking for a bot that anyone can use to make chat more fun. We’ve seen games, we’ve seen song 
requests, we’ve seen loyalty points, but we haven’t seen anything that *creates* content. What about a bot that scrapes the web for fun 
facts about the game a broadcaster is playing? Or finds and links to a relevant GIF that captures a moment? Maybe a bot that takes the 
pulse of Twitch and finds the most popular meme of the last 10 minutes? What kind of content would make chat more fun, and how could a 
bot find it and surface it?

You'll find some links below to help you on your journey to creating an awesome chatbot for Twitch. You will also find the code to a 
simple JavaScript chatbot that can help demonstrate how to interact with chat on Twitch. This particular bot uses JavaScript, but you 
can use any language you would like. The project structure section will give you a quick overview of this code.

Good luck and have fun!

## Important links
* Getting started documentation for the Twitch platform: https://dev.twitch.tv/docs 
* Overview of the Twitch chat structure: https://dev.twitch.tv/docs/irc 
* Twitch authentication guide (necessary for connecting to chat): https://dev.twitch.tv/docs/authentication
* The Twitch Developers forums are a great place to find existing questions and answers: https://discuss.dev.twitch.tv 

### Structure
`simple-chatbot.html`
Provides the user interface for the leaderboard and calls into the `chatClient` to connect to Twitch chat.

`simple-chatbot.js`
Provides all of the inner workings for the chat bot including connecting, sending user credentials, and joining the correct channel. The leaderboard rendering code is also inside of this file.

`leaderboard.css`
Makes the leaderboard look...better than an unformatted table. Kappa.