# FYA - BACKEND :rocket:

### About
Backend of FYA Application!

 ![](/images/header.png)
 
### Installation
Follow the steps to start the application on you environment: 
1. Download and Install Docker at `https://www.docker.com/products/docker-desktop`
2. Run `docker run --name fya -e POSTGRES_PASSWORD={YOUR_PASSWORD} -e POSTGRES_USER={YOUR_USER} -p 5432:5432 -d postgres`
3. Run `npm i -g @adonisjs/cli` for install __AdonisJs__
4. Download the project `git clone https://github.com/KLineApps/FYA_Backend`
5. Set the environment variables in the file __env_example__ and save as __.env__
6. Run `adonis key:generate` to generate the key for application
7. Install the dependencies `npm install` or `yarn`
8. Run migrations: `adonis migration:run`
9. Start the server :D `adonis serve --dev`
<br><br>

## Open routes in Insomnia
[![Run in Insomnia}](https://insomnia.rest/images/run.svg)](https://insomnia.rest/run/?label=FYA&uri=https%3A%2F%2Fraw.githubusercontent.com%2Fgu1ma%2FFYA_Backend%2Fmaster%2Fexport_routes.json)

## Releases

  * 0.0.1 (Beta version)
    * User (Normal and Teacher) Sign Up.
    * User Sign In with session and logout.
    * Sports Sing Up 
    * Create Event 
    * Subscribe on event
  
## Technologies:
   **NodeJS, Yarn, NPM, Adonis, Docker, POSTGRES**

## Branches

![](/images/git.png)

Developed by [__KLineApps.__](https://github.com/KLineApps)

