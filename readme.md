# STEPS TO SET UP NODE PROJECT
1. mkdir new directory
2. cd into new directory
3. run npm init (or npm init-y)
4. if running just npm init, hit enter through steps (skip this step if npm init-y entered in step )
5. look for name of  entry point ('main') file -> this will be the js file we need to create
6. touch js file that matches name in main in json package

# RESOURCES
* https://www.w3schools.com/nodejs/ref_fs.asp
* https://www.w3schools.com/nodejs/nodejs_http.asp

# HINTS
* Don't upload node modules to Github. Touch .gitignore in your directory.
* You can ctl + c to quit nodemon

# STEPS TO SET UP EXPRESS APP
1. mkdir new directory
2. cd into new directory
3. Initialize node w/ npm init
4. Install express with npm i express
5. Create entry point file, follow steps 6-8
6. Import express module -> const express = require('express')
7. Create instance of express app -> const app = express()
8. Create home route
9. Run nodemon


# EXPRESS ROUTES
* Home route
    * const app = express()
    * app.get('/', (req, res) {
        res.send('text string')
    })