## LiskListen - Lisk Transaction Visualizer ##

This software is a reworked version of [**BitListen.com**](http://bitlisten.com/).

Realtime Lisk transaction visualizer written in Nodejs/HTML/Javascript. See and hear new transactions and blocks as they propagate through the Lisk Network.

### Building ###

The project is built and ready-to-go. If you change any of the javascript, you will need to re-build the `lisklisten.min.js` file using Grunt. If you haven't used Grunt before, here is a short tutorial:

1. [Install Node.js](https://nodejs.org/download/).

2. Install grunt-cli using `sudo npm install -g grunt-cli`.

2. Cd into the project directory and run `npm install` to install the proper Grunt version and dependencies for this project.

3. Run `grunt` to build LiskListen. Alternatively, run `grunt watch` and watch for and rebuild changes in the source files.

4. Use another terminal to run `npm start` to start the software. It will be available at http://localhost:3000

The compiled/minified script will be output to `lisklisten.min.js`.

### APIs and Libraries ###

LiskListen uses these libraries:

* [Howler.js](http://goldfirestudios.com/blog/104/howler.js-Modern-Web-Audio-Javascript-Library) by James Simpson

LiskListen uses these APIs:

* [Blockchain.info](https://blockchain.info/) WebSocket API (For BTC Transactions)
* [Bitstamp.net](https://www.bitstamp.net/) Web API (For Price Ticker USD/BTC)
* [Bittrex.com](https://bittrex.com/) Web API (For Price Ticker BTC/LSK)
* [Lisk Node](https://docs.lisk.io/docs) Web API (For Lisk Blocks and Transactions)

### License ###

If you distribute this project in part or in full, please attribute with a link to [the GitHub page](https://github.com/hirishh/lisk-listen). This software is available under the MIT License, details in the included `LICENSE.md` file.
