# Es2015 Starter

## Why

A tiny repository for easily experimenting with modern JavaScript.

## How 

**Note**: This assumes you have Node and npm installed. If not, do that first!

Clone this repository, then `cd` into your newly-minted directory and run the following:

```
$ npm i
$ ./run.sh
```

Navigate to `localhost:8080` and voilà! You're all set up. 

## Dear newer users:

### Getting started

I've tried to make this as easy as possible to get off the ground, because I remember what a pain it was to get started with this ecosystem. There is no clear-cut path, and there are so many choices! I tried to keep mine minimal. They are:

* Webpack (to build everything)
* Babel (for transpiling back down from ES2015 syntax)
* ESLint (to tell you why you're an idiot—hugely important!)

### More details

The `./run.sh` file starts Webpack's development server. This server is serving `index.html` from `build/`. Don't anything in `build/` at all! (Your changes will be overwritten.) Instead write to `src/main.js`. When this becomes unwieldy, do yourself a favor and look at MDN's introduction to the es2015 module system.
