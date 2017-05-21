# Nussbaum-Server

[![Build Status](https://travis-ci.org/ikarulus/Nussbaum-Server.svg?branch=master)](https://travis-ci.org/ikarulus/Nussbaum-Server)

This is currently not meant to be used in production.

As the Server provides a REST-based HTTP-API you can wire up any client you want, e.g. [the web client](https://github.com/ikarulus/Nussbaum-Client) (in development)

Usage: <https://gist.github.com/ikarulus/c57ae21442201fae89fa194c1e021f6d> (de)

## Install (using npm):
1. `git clone https://github.com/ikarulus/Nussbaum-Backend.git`
2. `cd` in your "Nussbaum-Backend" directory
3. `npm install`
4. Install [MongoDB](https://docs.mongodb.com/manual/installation/) and [Redis](https://redis.io/topics/quickstart)
5. Wire up MongoDB and Redis database connection in the configuration file
6. (Optional, for arch users) Start databases with `./start_dbs.sh`. Must be executable. For other distros you have to find your own way.
7. Launch via `node app.js` or `npm start`
