# hackathon2017

To test this program download node.js and bot framework channel emulator <br />
Also required is a Bing search API key <br />
Note: the name of the zip file is a joke name<br /> 

Description <br />
Takes a (city) location and answers various questions. In particular:<br />
  Are there any jobs in some field? <br />
  What does the city look like? <br />
  Is there crime in the city? <br />
Other things such as the weather are unimplemented <br />

Implementation <br />
The bot was implemented using Microsoft's LUIS API to interpret typed sentences. The API returned some string, which can be matched to a command. <br />
For images and other searches I used a Bing API, and implemented some scripts to display the search results <br />

