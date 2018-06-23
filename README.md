# Reveal JS Template

This is a [reveal.js](http://lab.hakim.se/reveal-js/) presentation, built with [Brunch](http://brunch.io).

The content of the presentation is also marked up with [Pug](https://github.com/pugjs/pug) for the author's own sanity.

Like any respectable Javascript project, this presentation has about a quintillion indirect dependencies.  The author guarantees that he has carefully inspected about none of them.  All of the content of this presentation is directly encoded in an HTML document and pretty much completely illegible without using a modern web browser with Javascript enabled.

On the other hand, it's not PowerPoint.


## WTF

All dependencies for building the presentation can be installed with Yarn.

https://yarnpkg.com/en/docs/getting-started

To install all dependencies to the `node_modules` subdirectory:

    yarn

To build the presentation and output files to the `public` subdirectory:

    yarn build
