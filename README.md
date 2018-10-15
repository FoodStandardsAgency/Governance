# Food Standards Agency GitHub Governance 
 
# Purpose  
The objective of this policy is to minimise accidental or unauthorised access to the Food Standards Agency’s (FSA) [GitHub](https://github.com) account, and projects including but not limited to the, applications, and information stored within.  
 
This guide covers all things related to accessing and using GitHub in the context of working on a Food Standards Agency (FSA) project(s). 

This document supports the FSA Information Security Policy and Acceptable Use Policy. It provides direction and support for the implementation of information governance and is designed to help FSA employees carry out the business of the FSA in a secure manner. By complying with this policy, the risks facing the FSA are minimised.  
 
# Introduction  
 
Individuals employed by or under contract to the FSA shall be granted access only to information that is required to fulfil their duties.  
 
This policy applies to:  
All employees (including temporary and agency workers), independent consultants and contractors 
Members of FSA Advisory Committees and FSA Board  
Third party organisations who require access to the FSA’s information systems and facilities should also be aware of the contents of this policy.  
 
# User Access Management  

User access management covers all stages of user access, from initial registration, through changes in role, to deregistration and revocation of access.  
 
The security of systems, networks, applications and databases is heavily dependent on the level of protection of user IDs, passwords, and other credentials that provide access to it. Hence, protecting the credentials that provide access to information is indirectly protecting the information.  
 
Identification and authentication of users and systems enables the tracking of activities to be traced to the person responsible.  
 
All employees shall have a unique identifier (user ID) for their personal and sole use.  
 
 
# User registration  

A process for user registration and granting access rights exists and includes:  
 
Creating A GitHub account 
Enabling two factor Authentication 
Joining the Food Standards Agency GitHub Organisation 
Joining a Team  
 
Authorised users are aware of their responsibilities for the protection of information within the application and where applicable users sign an appropriate agreement.  
 
Ensuring access is granted once authorisation is obtained  
 
# Creating a Git Hub Account 
 
Before you can do anything on GitHub you'll need to [create an account](https://github.com/join).  FSA staff should create one using their FSA details to use when working on Food Standards agency work.   

Whether you create an account or use an existing one, it must meet the following requirements;
- [Two factor authentication](https://help.github.com/articles/about-two-factor-authentication/) must be enabled
- Your profile must have the `Name` field populated with your full name .e.g. *John Smith*.
-A profile picture is not compulsory, but changing it from the default that Gitub provides will help your team members distinguish your contributions from theirs. 
 
# Two Factor Authentication 

Please follow the GitHub help guide for Two Factor Authentication also known as 2FA 
About two-factor authentication 
Guidance on how to configure two factor authentication  
  
# Joining the Food Standards Agency GitHub organisation 

All projects at the Food Standards Agency must be created under the [the Food Standards Agency organisation](https://github.com/FoodStandardsAgency). If you are a permanent member of FSA staff we will add you to it as and when required. Else if a contractor or working on behalf of a supplier you will be added as a [collaborator](https://help.github.com/articles/adding-outside-collaborators-to-repositories-in-your-organization/) on the specific projects or teams as required. 

Contact the IT Service desk or the Team Moderator to request access providing the following details; 
-GitHub User Name 
-Email address associated with your GitHub account 
-The Project you’ll be working on 
-Team(s) you require access to and the expected duration you require access for 
 
The IT Service desk will confirm with the Project/Team owner before granting access. 
 
## Joining a Team 
The IT Helpdesk and or the Team maintainer will endeavour to add you to the appropriate teams in a timely manner once your initial request has been submitted to the IT service desk.   All members of the organisation should be able to see [all our teams](https://github.com/orgs/foodstandardsagency/teams). If there is a team applicable to you or you are to begin working on a service you will need to contact the team's maintainer to ask to join it.

 
## Existing members who are contractors 
Some existing members of the Food Standards Agency organisation are contractors. This guidance came after we had been using GitHub for some time. New contractors and suppliers will be added as described in this guidance and existing users transitioned. 
User Maintenance 
 
## User maintenance within GitHub is administered by team Maintainers. 

As a team maintainer you are responsible for ensuring that the members of your team and the repositories you have access to are accurate. 
Not only is this important from a security perspective, but the 'teams' list is an important source of information for other users. 

## Review of Access Rights  
“Maintainers” should review members lists to ensure they are still applicable, and only those that require access should still have access to each team/repository.  
 
## Removal of Access  
On resignation of employment, team maintainers, will undertake a risk assessment and determine whether existing access rights of an individual should be reviewed and reduced whilst working out their notice.  
[NOT SURE HOW WE ENFORCE THIS TO NON FSA SYSTEMS - ADD INTO DEREGISTRATION PROCEDURE FOR LITTLEFISH WHO COULD REMOVE ACCESS TO ADMINISTER IN THE CASE OF GITHUB BUT WIDER IMPLICATIONS FOR THE LIKES OF TRELLO & OTHER WEBBASED APPLICATIONS HOW WILL USER KNOW IF SOMEONE LEAVES THE FSA QUITELY AND IS NOT PART OF THEIR TEAM]  
 
On completion of a project the project owner/sponsor will need to make a decision on; 
What contractors still require access and for how long 
What staff require access and for how long 
 
Team members that no longer have a business requirement to access the information within a project or team should be removed at the earliest opportunity and informed that they no longer have access to said Teams, Repositories or in some cases the no longer access to the Food Standards Agency GitHub organisation.  

## Monitoring System Access  
Systems will be monitored to detect deviation from the Access Control Policy and record events to provide evidence in case of security incidents.  
 
Designated employees responsible for the following areas must establish the logging and monitoring requirements for the relevant purposes:  
• Security  
• Incident investigations  
• Audit  
• Fraud  
• Legal 
 
The system administrator does not have the authority to decide who should have access to what information. This is a business decision and is the responsibility of the Project/Team Maintainer.  

# New Projects

Please see the link for starting new projects

- [New projects](new_projects.md)


## Creating a new team
If you need a new team contact the Data Team. They will need

- The name of the service / project (please avoid acronyms to help support new users)
- A description (one sentence long)
- Username of the team maintainer
- A list of repositories the team requires access to

Once created it will then be up to the maintainer to [add new members](https://help.github.com/articles/adding-organization-members-to-a-team/) to the team.

### Being a team maintainer
As a team maintainer you are responsible for ensuring that the members of your team and the repositories you have access to are accurate.

Not only is this important from a security perspective, but the 'teams' list is an important source of information for other users.

## Repositories
Repositories are where we actually store our content (mainly code) on GitHub. All members of the  organisation have *Read* access to all repositories, both public and private.

### Create a new repo

The [New projects](new_projects.md) guide covers what you need to do to create a new repo or 'project'.

### Collaborators & teams

This refers to a tab in the `Settings` area of a repo. Its here you control which teams have **write** access to the repository.

Teams should only ever be given write access

- All members have *Read* access so granting a team this is meaningless
- Teams represent all members of a service, however not all of them should have *Admin* access

The administrator for each repo will be added as a **Collaborator**. Using GitHub's available functionality this is seen as the best solution

- It avoids creating *Admin only* teams for each service
- It helps distinguish who is the administrator for a repository

<img src="collaborators_teams.png" alt="Collaborators & teams" style="width: 600px;"/>

Also added as *Collaborators* will be any contractors or suppliers who require access to the repo. Their access should be set to either *Read* or *Write*. Only if the repo is being maintained by a third party, such as a supplier will a collaborator be given *Admin* access.

### Being a repository admin

If you are the administrator for a repository it's your responsibility to ensure the repo has been set up and maintained in accordance with [New projects](new_projects.md) guide.

It is also on you to ensure **Collaborators & teams** reflects who should have access to the repository.
 
# [Working on Git Hub](https://guides.github.com/) 
 
## [Understanding the GitHub flow](https://guides.github.com/introduction/flow/) 
GitHub Flow is a lightweight, branch-based workflow that supports teams and projects where deployments are made regularly. This guide explains how and why GitHub Flow works. 
 
## [Getting Started with GitHub Pages](https://guides.github.com/features/pages/)
GitHub Pages are a great way to showcase some open source projects, host a blog, or even share your résumé. This guide will help get you started on creating your next website. 
 
## [Git Handbook](https://guides.github.com/introduction/git-handbook/)
Learn about version control—in particular, Git, and how it works with GitHub 
 
## [Forking Projects](https://guides.github.com/activities/forking/)
Ever find a project on GitHub that you want to work on? Find out how you can contribute with Forking. 
 
## [Be Social](https://guides.github.com/activities/socialize/)
On GitHub there are many people and many projects to explore. Keeping up with the work that's done with them and showing your interest is easy. 
 
## [Making Your Code Citable](https://guides.github.com/activities/citable-code/)
Learn how to make your code citable in academic literature by assigning a Digital Object Identifier to your GitHub repository. 
 
## [Mastering Issues](https://guides.github.com/features/issues/)
GitHub is great for managing all of the information around the code. This guide helps explain our issue tracking system and how to keep up to date with issues you’ve participated in. 
 
## [Markdown](https://guides.github.com/features/mastering-markdown/)
￼Markdown is a lightweight and easy-to-use syntax for styling all forms of writing on the GitHub platform. 
 
## [Documenting your Projects on GitHub](https://guides.github.com/features/wikis/)
Creating documentation for your GitHub projects allows other developers to understand your work more easily, so that they can collaborate on your projects more effectively. 
 
 
# [Best Practice](https://resources.github.com/videos/github-best-practices/)
 
Includes 

## [Continuous Integration and Continuous Delivery](https://youtu.be/xSv_m3KhUO8)
Learn how Continuous Integration, Continuous Delivery and Continuous Deployment can help you ship better software, faster. 

## [Workflow Strategies](https://youtu.be/aJnFGMclhU8)
Two of the most popular workflow strategies in use today are the GitHub Flow and the Git Flow. Learn about the differences and some of the tools available to help you manage your work on GitHub. 

## [Managing Projects](https://youtu.be/nI5VdsVl0FM)
To categorize, prioritize, and manage your work, GitHub gives you a set of flexible tools like Labels, Milestones, and Projects, as well as robust APIs which let you craft a workflow that suits your needs. 

## [Quality Control](https://youtu.be/gJDtC_tp5w4)
Incremental measures woven into each step of your workflow helps you maintain software quality without sacrificing productivity. Learn the basics of Pre-receive Hooks, Status, and Protected Branches. 

## [Finding What You Need](https://youtu.be/F1ss7Lv15cw)
GitHub keeps a searchable index of all Repositories, Issues, Pull Requests, and Wikis. Learn about the tools available to help you find what you need, fast. 

## [Getting Insight Into Work](https://youtu.be/wq1LGr2j1Fw)
A GitHub project’s pulse, graphs, and branch statistics keep the focus on developers by giving you insights that help you ask the right questions, have conversations, and take thoughtful action. 
