# polymer-tutorial
CMP255 Implementation of the "Polymer in 10 minutes" tutorial code

This repo tracks [this tutorial](https://www.polymer-project.org/docs/start/creatingelements.html). 
To use:

Use the `ln -s` command to link the index.html-<name> to index.html

Here is an example for the "name-tag" example 
`ln -s index.html-name-tag index.html`

Note also you must run `npm install` after cloning this repo before running

You can run a "background web server" using this command: 
`forever --uid "polymer" start app.js`

Note this server runs on port 8002!

(Also note: I'm in the process, so far unsucessful, to get these demos working with Cordova.  You will see some things in the repo related to that)
