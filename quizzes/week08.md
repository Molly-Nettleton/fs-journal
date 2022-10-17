# Deploying Applications

**1.** What is the package.json file used for?
<!-- enter you answer in the space below -->
```
It is the heart of the node project. records important metadata which is required for publishing to NPM, defines functional attributes of a project that npm uses to install dependancies, run scripts, and identify entry point to your package.
``` 
**2.** At what level of your project do you need package.json when deploying your application? Why?
<!-- enter you answer in the space below -->
```
Route, use to give npm to identify the project, takes care of dependencies.
```
**3.** What command will ensure that your Vue code is compiled properly for deployment?
<!-- enter you answer in the space below -->
```
npm run build command
```
**4.** _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.
<!-- enter you answer in the space below -->
```
.env and env.js
```
**5.** What are the two ways to view the logs from your Heroku app.
<!-- enter you answer in the space below -->
```
$ heroku logs or view logs with the heroku dashboard
```
**6.** How do you update an app already deployed on Heroku?
<!-- enter you answer in the space below -->
```
Clone the repository from GitHub to your local device: git clone <YOUR HTTPS URL FROM GITHUB>
Make your changes, and commit them to GitHub
Login to your Heroku account
Set remote for your project
Push to Heroku master to deploy updates
```
**7.** Why is branching important to version control?
<!-- enter you answer in the space below -->
```
Branching allows the developer team to easily collaborate inside of one central code base
```
**8.** When should code review happen?
<!-- enter you answer in the space below -->
```
after all automation checks and before the working branch merges with the main branch
```
**9.** What is the term used to define combining two branches?
<!-- enter you answer in the space below -->
```
Merge
```