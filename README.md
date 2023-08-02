## File structure
#### `server` - Holds the server application
- #### `config` - This holds our configuration files, like mongoDB uri
- #### `.env` - Create .env file in config folder and set given variable and value
        ```
            PORT = 
            DB_URL = 
            JWT_SECRET_KEY = 
            JWT_EXPIRES = 
            ACTIVATION_SECRET = 
            SMPT_HOST = 
            SMPT_PORT = 
            SMPT_PASSWORD = 
            SMPT_MAIL = 

        ```
- #### `controllers` - These hold all of the callback functions that each route will call
- #### `models` - This holds all of our data models
- #### `routes` - This holds all of our HTTP to URL path associations for each unique url
- #### `tests` - This holds all of our server tests that we have defined
- #### `server.js` - Defines npm behaviors and packages for the client
#### `package.json` - Defines npm behaviors like the scripts defined in the next section of the README
#### `.gitignore` - Tells git which files to ignore
#### `README` - This file!

#### Create new folder under root folder name `uploads`
