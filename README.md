A little repo to try out webpack with react and hot code replacement.

It's an up to date version of https://robots.thoughtbot.com/setting-up-webpack-for-react-and-hot-module-replacement

- Changing app.js causes a full page load.
- Changing greeting.js updates the js in place.
- Neither is instant. Even the hot reload takes about a second.
  - Phoenix is that fast for a full page reload, so it might not be very useful in a phoenix app. Unless it can avoid reloading heavy things in javascript.

## Setup

    npm install
    source paths.env
    webpack-dev-server --hot --inline
