# zeGlicemia

# A simple website to assistant people to view and monitor their blood glucose

## Why this project ?

I'm a diabetic, so I know how hard can be, you have a total idea about how good your bloog glucose has been doing along the days or weeks, and I know how hard can be to parents or doctors to see how long their patients or children are going their blood glucose. So thinking about it, I descided to do this website, to help me, and help another people, to have a best ideia about their blood glucose along the days, and help parents and doctors to help the people their love, to have a best life. The project is using React Hooks to front, node.js with express to back and PostgreSQL to database, know more in the **Stacks** area.


## Environment Dependencies

- **[[NVM(Node Version Manager)](https://github.com/nvm-sh/nvm)]** 0.39.1 or higher...
- **[[Node.js](https://nodejs.org/en/download/)] by (NVM)** 16.15.1 or higher...
- **[[VS Code](https://code.visualstudio.com/download)]** 1.67.2 or higher...
- **[[Docker](https://docs.docker.com/engine/docker-overview/)]** 20.10.15 or higher...
- **[[Docker Compose](https://docs.docker.com/compose/)]** 1.29.2 or higher...

> **Note:**
>
> - _I'm using this environment dependencies to build the aplication, if you want to run it in your machine, you need to have them too._
> - _The execution of this project, it was in a **Desktop Ubuntu 20.04 LTS (Focal Fossa)** machine._

## Supporting Documentation

**in progress...**

## Stacks

- **App**
  - **docker-compose**
  - **GIT**
  - **Node.js**
    - **FrontEnd**
      - **docker**
      - **React.tsx**
        - **React Hooks**
        - **React Router**
        - **React Redux**
      - **Bootstrap**
      - **CSS3**
      - **in progress...**
    - **BackEnd**
      - **docker**
      - **Express**
      - **JWT**
      - **Sequelize**
      - **in progress...**
    - **Database**
      - **postgreSQL**
        - **Heroku Postgres**
      - **in progress...**
  - **tests**
    - **E2E**
      - **Mocha**
      - **chai**
      - **sinon**
    - **FrontEnd**
      - **Mocha**
      - **chai**
      - **sinon**
    - **BackEnd**
      - **Mocha**
      - **chai**
      - **sinon**
  - **CI/CD**
    - **Actions GitHub**
  - **Deployment**
    - **FrontEnd**
      - **Vercel**
    - **BackEnd**
      - **Heroku**
    - **Database**
      - **Heroku**

### Explain Stacks:

To geral app, we are using docker-compose to controll all containers below, GIT to have a best version the code when we can have branchs to front and back, we will use github to CI/CD controll, and the deployment are in Heroku, to back and database, and vercel to front. To tests, I decided have two diferents strategys, tests E2E, to have a geral behavior of the application, and unit tests to have totaly sure I know exactly when it's broken.

All app it will runing with node, and the individual aplication will have their own containers. On front, I will use React, to have a better control of the DOM, and have must control in internal staments. I will use some of the most popular React librarys to help me to construct this application, React Router DOM, to a better control route control and React Redux to have a shared statment to all components. Bootstrap to give facility to contruct a beauty application, and CSS3 to change some bootstrap styles. To back, I will use a Node server, with express to build a web application more easily, JWT to authenticate how are accesing our application, and a ORM called Sequelize, to easily the process of manutention the code.

## Building the application

To run this application on your machine, you need to check your **environment dependencies**, on **Environment Dependencies** has the necessary environment dependencies, and the link to their documentation, where which have the installation mode and version control.

### Run in your machine

#### Open your Linux Terminal:

 ```bash

# First, you need to clone de repositoy in your machine, to this, follow the steps below
~$ git clone git@github.com:viniciusoliveirabittencourt/zeGlicemia.git

~$ cd zeGlicemia

# After this, you will need to install all depedencies
# This command will run the necessary dependencies to run the tests
~/zeGlicemia$ npm install

# Now, enter in the backend directory, to run all commands necessary to run backend
~/zeGlicemia$ cd backend
~/zeGlicemia/backend$ npm install

# Now, enter in the frontend directory, to run all commands necessary to run frontend
~/zeGlicemia$ cd frontend
~/zeGlicemia/frontend$ npm install

 ```

After all of this, you can run the apps, and see them work on your machine!
