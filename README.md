# RIDR
Ride sharing companies such as Uber and Lyft are creating the future for how people commute. Lyft currently provides one million rides per day, while Uber has recently reached 5 billion rides. Consequently, traditional taxi services are struggling to keep up. Both Uber and Lyft have their own application which users can request rides through, while the majority of traditional cab services do not. The proposal of RIDR is to utilize the YELP!, Lyft, and Uber API in order to combine all of these services into one app. This will allow us to provide users with the chance to see all their available ride options without having to download multiple apps or knowing what local taxi companies are available. With enough users, this model could encourage competitive pricing and lower surge rates.
# Development Environment 
RIDR is built using the MERN stack. MERN stands for MongoDB, Express, React, Node. This stack is extremely efficient for small teams because it utilizes one programming language (javascript) in order to build the entire application. 
All code will be checked into Github through git. Code will be tested with CI through a Circleci webhook that is activated each time code is pushed to the remote repository. Any IDE or text editor may be used to write code, although Visual Studio code is preferred. Production code will sit in a Heroku container running on test dynos during development.
# System Development Requirements
In order to run development for this project, you will need to have NPM / Node and React installed.  Check the resources section on the GitHub for more in depth help. This environment is easily setup on a Unix based system such as OSX, which is what was used by the RIDR team. Windows users may need to do more research to get the proper packages configured to run RIDR development. Once Node and React are installed follow the following steps:

First clone the code off the GitHub.

Second we will need to install all dependencies. CD into the server directory, and run the command npm -i. This will look into your package.json file and automatically install all the packages that you will need.

After running the above step, you can fire up the development server. At the server directory, run the command npm run dev. This will concurrently run both the front end and back end servers. Navigate to localhost:3000 in your browser if you are not automatically kicked there. Make sure JavaScript and locations are enabled for the browser.
# RIDR as it stands
RIDR has no plans to be released to the public as a functioning application but the source code has been listed publicly on GitHub for anyone to use. The Heroku server used for the production version of the app will shut down eventually. RIDR was a class project and cannot go into production because of the terms of use with Uber and Lyft being used as competitors with their API's. As it stands our Lyft API key has been revoked and is invalid. 
