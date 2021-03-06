# Black Jack server

[![Build Status](https://travis-ci.org/oenstrom/ramverk2-blackjack-server.svg?branch=master)](https://travis-ci.org/oenstrom/ramverk2-blackjack-server)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/oenstrom/ramverk2-blackjack-server/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/oenstrom/ramverk2-blackjack-server/?branch=master)
[![Code Coverage](https://scrutinizer-ci.com/g/oenstrom/ramverk2-blackjack-server/badges/coverage.png?b=master)](https://scrutinizer-ci.com/g/oenstrom/ramverk2-blackjack-server/?branch=master)
[![Build Status](https://scrutinizer-ci.com/g/oenstrom/ramverk2-blackjack-server/badges/build.png?b=master)](https://scrutinizer-ci.com/g/oenstrom/ramverk2-blackjack-server/build-status/master)
[![Maintainability](https://api.codeclimate.com/v1/badges/a5ea321a90f97fe77893/maintainability)](https://codeclimate.com/github/oenstrom/ramverk2-blackjack-server/maintainability)
[![BCH compliance](https://bettercodehub.com/edge/badge/oenstrom/ramverk2-blackjack-server?branch=master)](https://bettercodehub.com/)

1. Clone the repo.
2. `npm install`
3. `npm start`
4. Open `http://localhost:3000`
5. Play around in the console.

Available events
```
"join room"    => socket.emit("join room", "room1");
"list rooms"   => socket.emit("list rooms");
"leave room"   => socket.emit("leave room");
```
Results are logged in the server terminal.

More info to come.

## Test
* Run `npm test` to run linters and tests.
* Run `npm test1` to test on Node 9 (alpine) using docker.
* Run `npm test2` to test on Node 8 (alpine) using docker.
* Run `npm test3` to test on Node 7 (alpine) using docker.
* Run `npm coverage` to generate code coverage.
