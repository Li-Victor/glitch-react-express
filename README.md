# React with Express In Glitch

React app with express boilerplate for [**Glitch.com**](https://glitch.com/). 

Uses version 0.9.5 react-scripts from create-react-app. Version 1.x react-scripts goes over the limit of space on the glitch container.

[**Project Link**](https://glitch.com/edit/#!/react-express). Feel free to remix it to try for yourself.

## Updating React

**Make sure the start script from package.json is `"start": "node index.js"`**. From the top-left `Project Info` menu, click on `Advanced Options` and then `Open Console`. A new tab with a terminal for your project will popup. Enter the command `yarn build`. You can close the terminal when it is finished building.

## Live updates coming from create-react-app

If you want to have the live change updates from create-react-app, go to package.json and change the start command to be `cd views && yarn start`. So it should be `"start": "cd views && yarn start"`. When you're done with live updates with react, **follow the instructions from the section `Updating React` exactly**.

This project is an extension of https://support.glitch.com/t/create-react-app-support/1295/2, and [**example glitch project**](https://glitch.com/edit/#!/5-passwords) from this blog post https://daveceddia.com/create-react-app-express-production/
