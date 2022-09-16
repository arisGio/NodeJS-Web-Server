# <a href="https://nodejs-web-server.netlify.app/">NodeJS Web Server</a>
    - First steps in learning Node.js. Creation of a simple Node.js web server to handle HTTP requests.
    
# TECH STACK & TOOLS
    - Visual Studio Code
    - HTML5
    - JavaScript
    - Node.js
    - github.dev
    
# GOALS
    - get to know how to use GitHub together with VS Code
    - introduction to node.js through a simple example
    - create a web server using node.js
    
# WHY
    - a way to run JavaScript outside of the browser
    - desktop apps, servers, anything that you want to do with JS
    
# STEPS
    - create a server
    - require a module/library called http
        used to start the server
    - tell it to start listening to a port
    - enrich it or refine with other things too after the above basic steps
    
# RUN SERVER
    @ terminal > node app.js
    
# KILL SERVER
    @ terminal > ctrl + c
    
# RESTART SERVER
    - everytime you make a change > restart the server
    
# TERMINAL
    - if terminal is not shown in VS Code, goto View > Terminal
    
# How To Use GitHub with Visual Studio Code | GitHub VSCode showtime
    https://www.youtube.com/watch?v=aUhl3B6ZweQ&ab_channel=CoderDave
    1) Source Control Management
    source control > clone repo > clone from GitHub > login > choose repo > choose local folder
    --> after doing changes
    source control > stage changes (+) > write message > commit code locally (checkmark)
    --> if changes are ready for github too
    > ... > Push > code uploaded to github

# Node.js INSTALLATION
    - DOWNLOAD from nodejs.org the LTS (long term support) version
    - follow INSTALLation steps
    - https://stackoverflow.com/questions/19202007/making-sure-usr-local-bin-is-in-my-path-on-mac
    echo $PATH 
    /usr/local/bin:/usr/bin:/bin:/usr/sbin:/sbin:/Users/alberteinstein/apache-maven-3.8.4/bin

# SERVER RESPONDING [PLAIN TEXT]
    - implement function
    - return a response object
        'Hello Node'
    - first RUN the SERVER
    - then OPEN BROWSER & GO to localhost:3000 where server is listening
        see 'Hello Node'
    - killing the server & refreshing the page gives you 'The site cannot be reached'

# RENDER HTML
    - render html from our web server rather than plain text
    - create a HTML file, index.html, that we want to render
    - generate outline of html document [boilerplate code]
        @ index.html > ! + enter

# SEND HTML
    - tell browser that we are going to write html
    - 200 is a good status code
    - tell browser to parse it as html
    - import library/module fs for file handling that we need
    - 404 status --> means NOT FOUND
    - data: all the information inside index.html

# GITHUB.DEV UTILIZATION
    - from GitHub > use github.dev to make changes online to a repo
    - like an online version of local VS Code Editor

# CHOOSE BRANCH
    - when using github.dev to the bottom left of VS Code you can choose the BRANCH
    - when working alone you should use only a main BRANCH
    - no need to create a development BRANCH
