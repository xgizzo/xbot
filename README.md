# xbot
![xbot](https://github.com/xgizzo/xbot/blob/master/assets/xbot2.png)

The Xbot Project is a work in progress to Automated and Secure CI/CD pipelines. This project is build on GitHub and uses the Probot framework to get up and running quickly.

The first part of the PoC is to Automate the Protection of all Master Branches when a repository is created. The Master Branch is where all code and artifacts get deployed, so protecting this is a good start for an automated pipeline.

Secondly we want to automate the creation of new issue in the newly created repository, this informs any users of all restrictions applied as well as any prior information a user might need to get started.

Thirdly we want to introduce Actions, these will be used for creating workflows for our CI/CD Pipeline. 



### Current Initial Setup

```
### -------- Step 1 --------
Create a new GitHub Application with Probot.
Follow the instructions here:

https://probot.github.io/docs/development/#configuring-a-github-app ; 

###  -------- Step 2 --------
Install the Probot Settings App in your GitHub Repository
https://github.com/probot/settings

### -------- Step 3 --------
Deploy an Action to run the Probot Settings App
https://github.com/marketplace/actions/github-action-to-run-probot-settings

### -------- Step 4 --------
Install the Application that creates an Issue on New Repo creation

https://github.com/migarjo/probot-create-issue-on-repo-creation

### --- Developer Tools ---
$ npm install -g truffle
```

### Project File Structure
This is 
```
