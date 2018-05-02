# hackathon2017

To test this program download node.js and bot framework channel emulator
Also required is a Bing search API key
Note: the name of the zip file is a joke name

Description\n
Takes a (city) location and answers various questions. In particular:
  Are there any jobs in some field?
  What does the city look like?
  Is there crime in the city?
Other things such as the weather are unimplemented

Implementation
The bot was implemented using Microsoft's LUIS API to interpret typed sentences. The API returned some string, which can be matched to a command.
For images and other searches I used a Bing API, and implemented some scripts to display the search results

