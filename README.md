Poslpo

This website is built using Docusaurus, a modern static website generator.
Installation

ruby

$ yarn

Local Development

ruby

$ yarn start

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.
Quick Start ⏱️

Understand Docusaurus in 5 minutes by playing!

Create a new Docusaurus site and follow the very short embedded tutorial.

Install Node.js and create a new Docusaurus site:

bash

npx create-docusaurus@latest my-website classic

Start the site:

bash

cd my-website
npx docusaurus start

Open http://localhost:3000 and follow the tutorial.

Tip: Use docusaurus.new to test Docusaurus immediately in your browser!

Or read the 5-minute tutorial online.
Build

ruby

$ yarn build

This command generates static content into the build directory and can be served using any static contents hosting service.
Deployment

Using SSH:

ruby

$ USE_SSH=true yarn deploy

Not using SSH:

javascript

$ GIT_USER=<Your GitHub username> yarn deploy

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the gh-pages branch.

Comparison with other tools

Across all static site generators, Docusaurus has a unique focus on documentation sites and has many out-of-the-box features.

We've also studied other main static site generators and would like to share our insights on the comparison, hopefully helping you navigate through the prismatic choices out there.

Feel free to further customize or adjust the content as needed. If you have any more changes or need additional assistance, just let me know!
