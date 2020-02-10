# XbotNation
![xbot](https://github.com/xgizzo/xbot/blob/master/assets/xbot2.png)

The XbotNation Project is a work in progress to Automated and Secure CI/CD pipelines. 
This project is build on GitHub and uses the Probot framework to get up and running quickly.

**Automate the Protection of all Master Branches** when a repository is created. 
The Master Branch is where all code and artifacts get deployed, so protecting this is a good start for an automated pipeline.

**Automate the creation of new a issue in the newly created repository**, this informs any users of all restrictions applied as well as any prior information a user might need to get started.

**Introduce Actions**, these will be used for creating workflows for our CI/CD Pipeline. 



### Current Initial Setup

 
**Step 1 : Create Webhook to listen to Organisation Events**

`Setup a Webhook to listen to Organisational Events. Also make sure you give it permissions for Repository & Issues Events`

[Setting Up a Webhook on Github](https://developer.github.com/webhooks/creating/)

**Step 2 : Automate Master Branch Protection**

`Install the Probot Settings App in your GitHub Repository. Follow the instructions in the link below`

[Probot Settings App](https://github.com/probot/settings)

**Step 3 : Install Action to run the Branch Protection Workflow**

`Deploy an Action to run the Probot Settings App. Follow the instructions in the link below`

[Probot Actions](https://github.com/marketplace/actions/github-action-to-run-probot-settings)

**Step 4 : Install Issue Generator for Newly Created Repos**

`Install the Application that creates an Issue on New Repo creation. The application also generates @Mentions, lists Master    Branch protection permissions and other information about the repo`
`Mirror and deploy the application, use the link below`

[Probot Create Issue on Repo Creation](https://github.com/migarjo/probot-create-issue-on-repo-creation)


**Step 5 : Deploy your Application on Glitch & Heroku**

`Deploying your applications to Glitch or Heroku then you don't have to worry about tunneling to your laptop with Ngrok or Smee`

[Deploy Probot GitHub App](https://probot.github.io/docs/deployment/)



### Project Repositories

[Xbot Main Repo](https://github.com/xgizzo/xbot)

[Xbot Repo Settings](https://github.com/xgizzo/org-settings)

[Issue Generator](https://github.com/xgizzo/mirrored)


### Project Gist

[Acme Computers](https://gist.github.com/gizzoXYZ/222795870fea7a53237e75d1491bd8b4)

[Dunder Mifflin Technologies](https://gist.github.com/gizzoXYZ/9e2ea9c68e0e3e9280d013d45b0ddc15)
