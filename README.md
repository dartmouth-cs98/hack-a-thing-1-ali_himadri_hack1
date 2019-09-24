### Ali and Himadri Hack-a-Thing1

### Short description of what you attempted to build
We attempted to build an alexa skill that uses the Spotify Web Api. We thought it may be cool to have an alexa skill that lets you play a certain song based on the API data. With this, we aimed to explore the developer environment for making an alexa skill and also get more familiar with the spotify API and how to read and use API documentation in general.
### Who did what (if you worked with someone else)
We both worked on research and reading online resources about how similar projects are built. Together, we set up the Amazon ASK CLI developer console through Himadri's account and registered a spotify application. We then worked through the setup together. We got to a point where on the Alexa app we could view the skill and log in with the spotify account. Then we encountered some errors when beginning to access the data and Himadri worked more on fixing that and navigating the Amazon github integration and some inherent issues with the Alexa Skills Kit. Ali at this point focused on getting a separate app working with the Spotify API through the online tutorial.
### What you learned

Followed the following tutorials: 
- https://developer.spotify.com/documentation/general/guides/authorization-guide/
- https://developer.amazon.com/docs/custom-skills/steps-to-build-a-custom-skill.html
- https://api-university.com/blog/part-1-registration-with-oauth-provider/
- https://www.youtube.com/watch?v=vsEaGjPPLqM
- https://www.hackster.io/mathwuy/what-s-that-song-alexa-skill-with-spotify-6bfa61
- https://github.com/spotify/web-api-auth-examples
- https://github.com/thelinmichael/spotify-web-api-node

We learned how to set up and use AWS to host a backend for a web app and for the alexa skill. We also learned the alexa development cycle and how to send and process intents. Himadri also had little experience with javascript so working in node and learning how to code in js was extremely useful. We also both learned how to set up an Alexa Skill project and use the ASK CLI in order to create and deploy code. Finally, we learned a bit about github integration and connecting an API call with an ASK application.

### What didn’t work

We weren't able to link our Alexa input with the API due to some problems testing and deploying code in the ASK Console and we struggled to navigate Amazon's ASK git integration. Himadri is currently trying to figure out how to fix that - seems to be an issue with node.js (https://github.com/alexa/alexa-skills-kit-sdk-for-nodejs/issues/533).