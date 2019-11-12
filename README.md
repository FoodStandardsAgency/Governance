# Food Standards Agency GitHub Governance

## Introduction  

Individuals employed by or under contract to the Food Standards Agency (FSA) shall be granted access only to information that is required to fulfil their duties.

This policy applies to:  

- All employees (including temporary and agency workers), independent consultants, contractors,
members of FSA Advisory Committees, and the FSA Board
- Third party organisations who require access to the FSA’s information systems and facilities should also be aware of the contents of this policy

### Purpose  
The objective of this policy is to minimise accidental or unauthorised access to the [FSA GitHub](https://github.com/foodstandardsagency) account and projects.

This repository contains guidance for accessing and using the organisational GitHub account when working on an FSA project.

It provides direction and support for the implementation of information governance and is designed to help FSA employees carry out the business of the FSA securely.  

## User Access Management and Onboarding

User access management covers all stages of user access, from initial registration, through changes in role, to deregistration and revocation of access.

The security of systems, networks, applications and databases is heavily dependent on the level of protection of user IDs, passwords, and other credentials that provide access to it.  

Identification and authentication of users and systems enables the tracking of activities to be traced to the person responsible.

All employees shall have a unique identifier (user ID) for their personal and sole use.

Users must have read, understood and agreed to the:

- FSA Information Security Policy
- The Acceptable Use Policy

If you are FSA staff you are responsible for ensuring the contractors you are onboarding have read, understood, and agreed to these policies.

### User registration  

The process for user registration and granting access rights includes:

1. Create a GitHub account and meet the account requirements
2. Join the Food Standards Agency organisation
3. Join a Team  

### Creating a GitHub account

Before you can do anything on GitHub you'll need to [create an account](https://github.com/join). FSA staff should create one using their FSA details to use when working on Food Standards agency work.

#### Account Requirements

Whether you create an account or use an existing one, it must meet the following requirements;

1. [Two factor authentication](https://help.github.com/articles/about-two-factor-authentication/) must be enabled
2. Your profile must have the `Name` field populated with your full name i.e. `John Smith`
3. A profile picture is not compulsory, but changing it from the default will help your team members distinguish your contributions from theirs

**Users with access to our organisation will be reviewed periodically, those users who do not meet requirements one and two may be removed from the organisation without notice.**

### Joining the organisation

All repos at the Food Standards Agency must be created under the [Food Standards Agency organisation](https://github.com/FoodStandardsAgency).

If you are a permanent member of FSA staff you can be added by contacting the IT service desk.

Contractors and suppliers should be added to the organisation by the delivery or project manager that they report to as part of onboarding.

When contacting the IT service desk you will need to provide the following:
- GitHub User Name
- Email address associated with your GitHub account
- The project(s) you’ll be working on
- The team(s) you will need access to and the expected duration

The IT Service desk will confirm with the project or team owner before granting access.

### Joining a Team
We will endeavour to add you to teams in a timely manner once your initial request has been submitted to the IT service desk.

All members of the organisation should be able to see [all our teams](https://github.com/orgs/foodstandardsagency/teams).

If there is a team you are not a member of but feel you need to be, please contact the team maintainer.


#### Existing members who are contractors
Some existing members of the Food Standards Agency organisation are contractors. This guidance came after we had been using GitHub for some time. New contractors and suppliers will be added as described in this guidance and existing users transitioned.
User Maintenance

### Users are managed by team maintainers

Team maintainers are responsible for ensuring that the members of a team and the repositories they have access to are up to date. This is important for security, and an important source of information for other users.

#### Review of Access Rights  
Maintainers should regularly review member lists to make sure they are up to date. Only those that require it should have access to each teams and repositories.  

### Removal of Access  
On resignation of employment, team maintainers, will undertake a risk assessment and determine whether existing access rights of an individual should be reviewed or reduced whilst working their notice period.

On completion of a project the project owner/sponsor will need to make a decision on;
- Which contractors still require access and for how long
- What staff require access and for how long

Team members that no longer have a business requirement to access the information within a project or team should be removed at the earliest opportunity and informed that they no longer have access to those teams, repositories or the organisation.  

### Monitoring System Access  
Systems will be monitored to detect deviation from the Access Control Policy and record events to provide evidence in case of security incidents.  

The system administrator does not have the authority to decide who should have access to what information. This is a business decision and is the responsibility of the project and/or the team maintainer.  

### Creating a new team
If you need a new team contact the service desk. They will need;

1. The name of the service / project (please avoid acronyms to help support new users)
2. A description (one sentence long)
3. Username of the team maintainer
4. A list of repositories the team requires access to

Once created it will then be up to the maintainer to [add new members](https://help.github.com/articles/adding-organization-members-to-a-team/) to the team.

### Being a team maintainer
As a team maintainer you are responsible for ensuring that the members of your team and the repositories you have access to are accurate.

Not only is this important from a security perspective, but the list of teams is an important source of information for other users.

## Repositories
Repositories are where we actually store our content (mainly code) on GitHub. All members of the organisation have **read** access to all repositories, both public and private.

### Creating a new repository

The [new projects](new_projects.md) guide covers what you need to do to create a new repository or project.

### Collaborators & teams

The settings of a repository is where you control which teams have **write** access to it.

Teams should only ever be given write access

- All members have *Read* access so granting a team this is meaningless
- Teams represent all members of a service, however not all of them should have *Admin* access

The administrator for each repo will be added as a collaborator. Using GitHub's available functionality this is seen as the best solution because it avoids creating *Admin only* teams for each service and it helps distinguish who is the administrator for a repository.


Other collaborators will be contractors or suppliers who require access to the repository. Their access should be set to either *Read* or *Write*. Only if the repo is being maintained by a third party, such as a supplier will a collaborator be given *Admin* access.

### Being a repository admin

If you are the administrator for a repository it's your responsibility to ensure the repo has been set up and maintained in accordance with [New projects](new_projects.md) guide.

It is also on you to ensure **Collaborators & teams** reflects who should have access to the repository.

The current licencing for the FSA GitHub organisation includes up to 50 private repo's.  It is the joint responsibility of all Project leads that use GitHub to ensure we don't go over this limit.

When a project has been completed the project owner should make the repo "Not Private" or store in the appropriate filemanagement location.

When a project has been completed its the responsibility of the Project owner to save the files and documentation appropriately.  At the time of writing the governance documentation Wisdom is the official records management system for the FSA.

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
