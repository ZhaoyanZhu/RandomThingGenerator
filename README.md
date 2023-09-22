# RandomThingGenerator
Generate random things with adv and noun

This is a website currently hold on the localhost:3000 that allows you to generate things, decribed by a out-of-sense adv.

I created two arrays, adv and noun, each of them contains a lot of words.
Each time, the post request is sent from the client, two random indexes will be generated within each of these two arrays length, 
and these two indexes will be used to access adv array and noun array to randomly get a adv and noun.
Concatening these two words, and send the concatenation back to the client.

Clone this repo.
Install all dependencies with npm install
Run the server with node index.js
Go to http://localhost:3000

