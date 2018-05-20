# Full Stack React

## Course resources:

 <https://docs.google.com/document/d/1ZVLphlOH0PEOUCd5v2UJVHiRSKuYjJI-AS4xQWYXmq8/edit>

## Node and Express

* Node: Javascript runtime used to execute code outside of the browser.
* Express: Library that runs in the Node runtime. Has helpers to make dealing with HTTP traffic easier.

## Heroku Deployment Checklist

* Dynamic Port Binding
  * Heroku tells us which port our app will use, so we need to make sure we listen to the port they tell us.
* Specific Node Environment
  * We want to use a specific version of node, so we need to tell Heroku which version we want.
* Specify start script
  * Instruct Heroku what command to run to start our server running.
* Create .gitignore file
  * We don't want to include dependencies, Heroku will do that for us.

## First Time Deploy

* Create Heroku account
* Committ our codebase to git
* Install Heroku CLI and Create App
* Deploy App with Git
* Heroku deploys project

## Subsequent Deploys

* Commit codebase with git
* Deploy App with Git

## Passport

* Passport Library Components
  * passport: General helpers for handling auth in Express apps
  * passport strategy: Helpers for authenticating with one very specific method (email/password, Google, Facebook, etc.)
* <https://passportjs.org>
* clientID
  * Public token - we can share this with the public.
  * Identifies our application with Google's servers.
* clientSecret
  * Private token - we don't want anyone to see this!