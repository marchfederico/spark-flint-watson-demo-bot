TechCrunch Disrupt demo bot

Dependencies -
    "async": "~0.2.8",
    "body-parser": "^1.15.2",
    "express": "^4.14.0",
    "fs": "0.0.1-security",
    "node-flint": "^4.1.1",
    "path": "^0.12.7",
    "watson-developer-cloud": "^2.2.0"

Use -

Easy to setup and use Spark bot skeleton based on Flint bot Framework by Nick Marus with integration to IBM Watson Conversation API.


## Running the server 

DEBUG=flint,bot,sparky node server.js

Configuration -
    1.Clone repository by creating a new workspace on cloud9 using clone option
    2.Create Spark Bot account at developer.ciscospark.com
    3.Setup IBM Watson conversation API per IBM instructions
    4.Rename config.example to config.js and add keys, username and ID'server
    5.Start server
