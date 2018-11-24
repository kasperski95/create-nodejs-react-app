React and Node.js starter.

# Packages used
* browser-sync - refreshes browser(s) on change
* nodemon - restarts server on server's code change
* express - web framework for node.js
* concurrently - runs server, browser-sync and bundler in one terminal
* wait-on - browsers are refreshed only if server is ready
* react stuff - component based websites
* babel stuff - converts jsx into js
* webpack - bundles all js or jsx files into one, and put it to the server folder

# Start
1. *git clone https://github.com/kasperski95/create-nodejs-react-app.git*
1. Open **Visual Studio Code**
1. *Terminal* -> *New Terminal*
1. Run **npm i** from VS Code's terminal
1. *Terminal* -> *Run build task* **(ctrl + shift + b)**

# Rules
* Webpack output files should satisfy following rule: *\*bundle.\** to be not included in git repository.
