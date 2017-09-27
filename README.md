# my-website
My personal homepage

# Self-hosting & Running
`server.js` is the server that my website is run on, meaning that it's locally hosted. If you cloned my website with Git (you probably did) and want to host locally, you'll get an error when trying to run `node server.js`. How do you fix it? Simple. Go to the website directory where `server.js` is stored and right-click, you then should see "Open command window here". Then, type:

`npm install body-parser --save`

`npm install express --save`

After you've installed express and body-parser, you're finished! Type `node server.js` into the command window and then type `localhost:<port>` into your browser's address bar.

Do **not** include the `< >` when you're typing `localhost:<port>`



Example of what you should do:

`localhost:3000`


In the example above, `3000` is the port. It doesn't have to be 3000, it could be something else. That's just an example. 

# Reporting bugs/issues
Make a PR/edit request. If it's more of a serious issue that you need to discuss with me, my email can be found here:

`void@void.cool`
