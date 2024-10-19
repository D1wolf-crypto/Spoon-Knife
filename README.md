### Well hello there!

This repository is meant to provide an example for *forking* a repository on GitHub.

Creating a *fork* is producing a personal copy of someone else's project. Forks act as a sort of bridge between the original repository and your personal copy. You can submit *Pull Requests* to help make other people's projects better by offering your changes up to the original project. Forking is at the core of social coding at GitHub.
{
    "name": "app-service-hello-world",
    "description": "Simple Hello World Node.js sample for Azure App Service",
    "version": "0.0.1",
    "private": true,
    "license": "MIT",
    "author": "Microsoft",
    "scripts": {
        "start": "node index.js",
        "lint": "eslint",
        "format": "prettier --single-quote --write *.js"    
    },
    "devDependencies": {
        "eslint": "^7.5.0",
        "prettier": "^2.0.5"
      },
    "dependencies": {
        "body-parser": "^1.19.0",
        "cors": "^2.8.5",
        "express": "^4.17.1"
      },
      "engines": {
        "node": ">=10"
      }
}
After forking this repository, you can make some changes to the project, and submit [a Pull Request](https://github.com/octocat/Spoon-Knife/pulls) as practice.

For some more information on how to fork a repository, [check out our guide, "Forking Projects""](http://guides.github.com/overviews/forking/). Thanks! :sparkling_heart:
