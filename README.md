# Food Standards Agency GitHub Governance

## Introduction  

Individuals employed by or under contract to the Food Standards Agency (FSA) shall be granted access only to information that is required to fulfil their duties.

This policy applies to:  

- All employees (including temporary and agency workers), independent consultants, contractors,
members of FSA Advisory Committees, and the FSA Board
- Third party organisations who require access to the FSA’s information systems and facilities

### Purpose  
The objective of this policy is to minimise accidental or unauthorised access to the [FSA GitHub](https://github.com/foodstandardsagency) account and projects.

These are the rules for accessing or using the organisational GitHub account when working on an FSA project.

They provide direction and support for the implementation of information governance and are designed to help FSA employees carry out the business of the FSA securely.  

## User access management and onboarding

User access management covers all stages of user access, from initial registration, through changes in role, to deregistration and revocation of access.

The security of our systems is dependent on protecting user IDs, passwords, and other credentials that provide access to them. Identification and authentication of users and systems enables the tracking of activities to be traced to the person responsible.

Users must read, understand, and agreed to:

- FSA Information Security Policy
- The Acceptable Use Policy

FSA staff are responsible for ensuring the contractors you are onboarding have read, understood, and agreed to these policies.

### User registration

The process for user registration and granting access rights includes:

1. Creating a GitHub account and meet the account requirements
2. Joining the FSA organisation
3. Joining a team  

### Creating a GitHub account

All users shall have a unique identifier for their personal and sole use. If you do not have one, you'll need to [create an account](https://github.com/join). FSA staff should create one using their FSA details to use when working on FSA services.

#### Account requirements

Whether you create an account or use an existing one, it must meet the following requirements:

1. [Two factor authentication](https://help.github.com/articles/about-two-factor-authentication/) must be enabled
2. Your profile must have the `Name` field populated with your full name i.e., `Hercules Rockefeller`

A profile picture is not compulsory, but changing it from the default will help your team members distinguish your contributions from theirs. We understand that some people are not comfortable having a picture of themselves on an online service, so you don't have to use your own face if you don't want to but please make it distinctive enough to distinguish your profile from others'.

**Users with access to our organisation will be reviewed periodically, and users who do not meet these requirements may be removed from the organisation without notice.**

### Joining the organisation

All repositories at the Food Standards Agency must be created under the [FSA organisation](https://github.com/FoodStandardsAgency).

If you are a permanent member of FSA staff you can be added by contacting the IT service desk.

Contractors and suppliers should be added to the organisation by the delivery or project manager that they report to as part of onboarding. The delivery manager should contact the IT service desk on their behalf.

When contacting the IT service desk you will need to provide the following:
- GitHub user name(s)
- The email address associated with those user(s)
- The project(s) you’ll be working on
- The team(s) to add the user to

The IT Service desk will confirm with the project or team owner before granting access.

### Joining a team
[Our teams](https://github.com/orgs/foodstandardsagency/teams) must be visible, secret teams are not permitted.

If there is a team you are not a member of but think you need to be, please contact the team maintainer.

#### Existing members who are contractors
Some existing members of the Food Standards Agency organisation are contractors. This guidance came after we had been using GitHub for some time. New contractors and suppliers will be added as described in this guidance and existing users transitioned.

### User roles
There are two roles that should be assigned to new users, `member` or `outside collaborator`. FSA staff should always be set up as members, outside collaborator should only be used for third-party supplier. It is not always necessary or desirable to make non-FSA users outside collaborators as you may want them to complete other administration of the team or repository on your behalf - we work on the principle of trusted relationships with our suppliers.

The final decision on which role is to be assigned to a user sits with the team maintainer.

For more detailed information on the difference between the two roles, please see the [help article](https://help.github.com/en/github/setting-up-and-managing-organizations-and-teams/permission-levels-for-an-organization).

### Users are managed by team maintainers
Team maintainers are responsible for ensuring that the members of a team and the repositories they have access to are up to date. This is important for security, and an important source of information for other users.

#### Review of access rights  
Maintainers should regularly review member lists to make sure they are up to date. Only those that require it should have access to each teams and repositories.  

### Removal of access  
On resignation of employment team maintainers must determine whether existing access rights of an individual should be reviewed or reduced whilst working their notice period.

On completion of a project the project owner/sponsor will need to make a decision on:
- Which contractors still require access and for how long
- What staff require access and for how long

Team members that no longer have a business requirement to access the information within a project or team should be removed at the earliest opportunity and informed that they no longer have access to those teams, repositories, or the organisation.  

### Monitoring system access  
The service will be monitored to detect deviation from the this policy and record events to provide evidence in case of security incidents.  

The system administrator does not have the authority to decide who should have access to what information. This is a business decision and is the responsibility of the project and/or the team maintainer.  

### Creating a new team
If you need a new team contact the service desk. They will need;

1. The name of the existing team, service, or project (please avoid acronyms to help support new users)
2. A description (one sentence long)
3. Username of the team maintainer
4. A list of repositories the team requires access to

Once created it will then be up to the maintainer to [add new members](https://help.github.com/articles/adding-organization-members-to-a-team/) to the team.

### Being a team maintainer
As a team maintainer you are responsible for ensuring that the members of your team and the repositories you have access to are accurate.

Not only is this important from a security perspective, but the list of teams is an important source of information for other users.

## Repositories
Repositories are where we actually store our content (mainly code) on GitHub. All members of the organisation have read access to all repositories, both public and private.

### Public or private repositories
Our current licence limits us to 50 private repositories. The FSA has a policy of working in the open and in most instances we should make our repositories public. If you need a private repository you will need to request this via the IT Service desk so that organisational administrators can review your request and archive or make public another repository if necessary.

**We do not currently have a formal set of criteria for allocating private repositories (this is being developed), in the interim, requests will considered on a case by case basis.**

### Creating a new repository

The [repositories](Repositories.md) guide covers what to do when creating a new repository or project.

### Teams, collaborators, and repositories

The repository settings page is where you control which teams have write access.

- All members of the organisation have read access so granting a team this level of permissions is meaningless
- Teams represent all members of a service, however not all of them should have admin access
- You can (and should) create a sub-team for those users who will be administrators, this can be done after the repository is set up

Other collaborators will be contractors or suppliers who require access to the repository. Their access should be set to either read or write. Collaborators should never have administrator access, if they require it then you should make them a team member.

### Being an administrator

Administrators should make sure the repository is set up and maintained in accordance with our [repositories guidance](repositories.md).

Administrators must ensure team membership and collaborators accurately reflects who should have access to the repository.

When a project ends the repository should be made public or deprecated entirely and all files moved to Wisdom as an official record.
