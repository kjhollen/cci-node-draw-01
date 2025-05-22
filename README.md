# Hello Node!

Building on our [simple node.js example](https://glitch.com/edit/#!/cci-node-express?path=README.md%3A1%3A0), this example adds socket.io to communicate real-time updates between connected users (clients) and the server.
The client side implements a very simple p5.js drawing app that sends mouse coordinates to the server when the mouse is dragged.
Then, the server sends those coordinates to all connected clients so that they can synchronize drawing.

[Node.js](https://nodejs.org/en/about/) is a popular runtime that lets you run server-side JavaScript.
This project uses the [Express](https://expressjs.com/) framework.
Please do not upgrade to Express version 5, which is incompatible with the version of node.js that Glitch uses.

_Last updated: 19 May 2025_

## Prerequisites

You'll get best use out of this project if you're familiar with basic JavaScript.
If you've written JavaScript for client-side web pages this is a little different because it uses server-side JS, but the syntax is the same!

## What's in this project?

← `README.md`: That’s this file, where you can tell people what your cool website does and how you built it.

← `public/style.css`: The styling rules for the pages in your site.

← `public/client.js`: The JavaScript for the site's front-end. This connects to a socket to talk to the server and contains our p5.js code.

← `public/index.html`: This is the main index for the site. In other Glitch examples, you may see HTML templates with libraries like Handlebars instead of an index.html

← `server.js`: The **Node.js** server script for your new site. In this example, we set up some simple socket communication in addition to serving HTML, CSS, and JS files.

← `package.json`: The NPM packages for your project's dependencies.

## Try this next 🏗️

___Want a minimal version of this project to build your own Node.js app? Check out [Blank Node](https://glitch.com/edit/#!/remix/glitch-blank-node)!___

![Glitch](https://cdn.glitch.com/a9975ea6-8949-4bab-addb-8a95021dc2da%2FLogo_Color.svg?v=1602781328576)

Note: this is a template developed by Glitch and uses Fastify instead of Express.
Both libraries are similar in function, but have different syntax.

## You built this with Glitch!

[Glitch](https://glitch.com) is a friendly community where millions of people come together to build web apps and websites.

- Need more help? [Check out our Help Center](https://help.glitch.com/) for answers to any common questions.
- Ready to make it official? [Become a paid Glitch member](https://glitch.com/pricing) to boost your app with private sharing, more storage and memory, domains and more.
