# Paragon MCP Client Starter
Built to demo how to build an MCP Client that can connect to an ActionKit MCP Server with dynamic authentication

## Setup
* Clone this repo
* Clone the ActionKit MCP Server Starter
* Create a `.env` file with the following details
```
PARAGON_USER=
PARAGON_PROJECT_ID=
SIGNING_KEY=
```
* Run `npm run build`
* Go through the ActionKit MCP Server instructions to build a js file
* From the root of this project, run `node build/index.js <path to MCP server/build/index.js`
