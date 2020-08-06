[homePage](https://henok-6411.github.io/reading-notes) 

## Gatsby JS

Gatsby is a React-based, GraphQL powered, static site generator. What does that even mean? Well, it weaves together the best parts of React, webpack, react-router, GraphQL, and other front-end tools in to one very enjoyable developer experience. Don’t get hung up on the moniker ‘static site generator’. That term has been around for a while, but Gatsby is far more like a modern front-end framework than a static site generator of old.

It uses powerful preconfiguration to build a website that uses only static files for incredibly fast page loads, service workers, code splitting, server-side rendering, intelligent image loading, asset optimization, and data prefetching. All out of the box. I didn’t believe the speed until I tried it myself.

You code and develop your site, Gatsby transforms it into a directory with a single HTML file and your static assets. This folder is uploaded to your favorite hosting provider, and voila. Overall think, part Jekyll, part create-react-app.

You may be thinking, “I have a nice web pack config I use”, or “create-react-app works for me”, or “Jekyll is fine for my blog.” Well, I think there are three things that make Gatsby very special versus these other tools.

First, is the way Gatsby uses GraphQL to build it’s data layer. What do I mean by that? Gatsby is made to collect your data from wherever it may be: Markdown, JSON, your favorite CMS, third party APIs, anywhere! And at build time, it creates an internal GraphQL server of all of this data. So in your react components, all of your data is queried at build time from that same place, in the same way through GraphQL.
