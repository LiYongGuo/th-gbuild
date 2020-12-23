# th-gbuild
tonghuafund front build tools
# Installation
    $ yarn add th-gbuild --dev
    #or npm
    $ npm install th-gbuild --save-dev

in your package.json

    "scripts": {
      "clean" : "th-gbuild clean",
      "build" : "th-gbuild build",
      "develop" : "th-gbuild develop"
    }
# CLI Usage
    $ th-gbuild <task> [options]
# e.g.
    # Runs the app in development mode
    $ th-gbuild develop
    # Builds the app for production to the `dist` folder
    $ th-gbuild build