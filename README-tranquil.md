How do I build this fusty javascript thing?

First install npm
`brew install npm`

Then install the project dependencies
`npm install`

Then build the project
`npm run build`

At this point all the fiddly bits will be in the dist directory. If you're doing this to build the tqd-visualizer, then you're done (the HTML files point to dist). If you're doing this independently, then you'll need an HTML file to make this javascript available to a browser. Look at the tqd-visualizer project for an example (index.html)
