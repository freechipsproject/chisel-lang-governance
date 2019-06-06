# Chisel Working Group (CWG) Provisional Constitution

### Table of Contents
* [Relationship to [CHIPS Alliance]](#relationship-to-chips-alliance)
* [Mission Statement](#mission-statement)
* [Technical Advisory Committee](#technical-advisory-committee)
* [Members](#members)
  * [Administrator](#administrator)
  * [Reviewers](#reviewers)
  * [Developers](#developers)
  * [Volunteers](#volunteers)
* [Collaboration Policy](#collaboration-policy)
  * [Communication Channels](#communication-channels)
  * [Development Policy](#development-policy)
* [Changing the Constitution](#changing-the-constitution)
* [TAC Voting](#tac-voting)
* [Code of Conduct (Contributors)](#code-of-conduct-contributors)
  * [Our Pledge](#our-pledge)
  * [Our Standards](#our-standards)
  * [Our Responsibilities](#our-responsibilities)
  * [Scope](#scope)
  * [Enforcement](#enforcement)
  
## Relationship to CHIPS Alliance

CHIPS Alliance’s Board of Directors will approve new projects, including Chisel and its associated projects.
We will be a “working group”. We will abide by the bylaws established by CHIPS Alliance.

## Mission Statement
The Chisel ecosystem is a stable, user-friendly platform for production-quality RTL generator development, 
designed to support the needs of a variety of RTL development communities, including industry, academia, and individuals.

It includes support for the “Chisel stack”, including but not limited to FIRRTL, Testers, Chisel Utilities, documentation, 
and administrative work.


## Members
The Chisel self-governance consists of five types of members: **TAC members**,
**administrators**, **reviewers**, **developers**, and **volunteers**.

### Technical Advisor Committee (TAC)
The role of Technical Advisory Committee (TAC) is to represent the interests of the
projects and members of the Chisel Working Group. This includes, but is not limited
to, facilitating communication and collaboration between members, as well as interfacing
with CHIPS Alliance on behalf of the Chisel community. Additionally, the TAC is
responsible for upholding the policies outlined in this document.

The TAC is made up of members of the community as well as one member appointed by
the CHIPS Alliance Board. The TAC and its members are responsible for setting high
level goals and interfacing with the CHIPS Alliance Board and other CHIPS Alliance
working groups.

Other responsibilities include: admit (and if necessary expel) project,
organize community meetings/conferences, resolve disputes between project
allocate funds, clarify procedures for each membership type, and publicize
Chisel projects.

Projects are admitted (or expelled) by a 2/3 vote of the TAC. A list of current
projects is maintained in a document in this repository.

The members are listed by name and Github username in a document within
this repository. Membership change is reflected by pull requests
against the membership list document. Members have the power to remove themselves.
Membership additions (or expulsions) require 2/3 approval of the current members
of the TAC.

#### TAC Chair
The chair of the TAC is selected from and by the TAC members by popular vote.
The chair's responsibilities are to schedule and run meetings of the TAC, as well
as count votes and enforce voting periods for any action that requires a vote.

The chair will serve until they step down or are replaced by a new vote of the TAC.
Chair elections generally occur during scheduled meetings, but in the event of an
absent or otherwise misbehaving chair, such a vote can be initiated by any TAC member
as a PR against the TAC membership document.

### Administrator
Consists of one lead and any number of additional administrators who direct a
given project and report progress to the TAC
They have the responsibility to represent the user community’s diverse set of
interests.

Administrators determine how underlying projects are managed, which may include
enforcing collaboration policies, and determining how contributors join the project.
They also resolve disagreements between Reviewers, Developers, Volunteers, and users.

Administrators have all of the rights and responsibilities of Reviewers.

### Reviewers
Reviewers are selected per project repository, and their primary responsibility is to maintain the health of the code 
repositories by enforcing a consistent coding style and good software engineering practices. Their second responsibility 
is to encourage community growth by mentoring enthusiastic contributors.

*Reviewers will be the members who most directly interact with the developer community, so it is of primary importance that 
they encourage a welcoming atmosphere.*

Reviewers are the only members who have write-privileges to their repository, so they must be active regularly such that 
development will not stall on their reviews. The procedure for becoming a Reviewer is outlined in the following Developers 
section.

Reviewers strictly subsume Developers (e.g. they also have all the rights and responsibilities of Contributors).

### Developers
Developers are the most common membership type, and is an entry point for enthusiastic community members. They have voting
rights for high-level directives as set by the administrators of a given project.

Anyone can become a developer by signing up and *signing the CLA*. In exchange for voting rights, a developer must commit to 
5 hours per month of development work on any Chisel project. This work can include:
* creating pull requests
* reviewing pull requests
* submitting issues
* discussing issues
* answering Stack Overflow questions
* attending meetings
* external contributions (registered on website via submissions)
  * writing blogs
  * additional documentation
* red lighting/green lighting releases

Developers who have been inactive for six months or more will be removed from the group.

A developer interested in becoming a reviewer should have a wide body of commits and begin reviewing submitted pull 
requests to practice and build up a body of reviews, both to demonstrate their expertise but also to increase their 
familiarity with the repository. These pull-requests will also require reviews from a Reviewer. Once a developer has 
had over 10 reviews on a project, they can submit a request to the administrators to become a Reviewer for that project.

Developers can contribute feedback by testing scheduled releases and fixes, and these members are critical to ensuring 
Chisel's backwards compatibility, as well as discovering bugs before a release. 

### Volunteers
Volunteers are people who want to contribute to a Chisel project, but do not commit to a regular contribution. They do 
not have voting rights, and no registration is required. Volunteers may attend development meetings. Volunteers may 
contribute through PR’s to Chisel repositories, and are encouraged to review and comment but they cannot accept PR requests. It is hoped that volunteers will become developers.

## Collaboration Policy
CWG’s standard communication channels and development policy is outlined as follows, and will likely be adopted for other 
associated CHIPS Alliance working groups.

## Communication Channels
High level leadership directives will be published via mailing list, and minutes of these discussions will be posted on the 
Chisel website.

All technical development discussions will be done either on Github with Github issues, pull requests, and comments, or via 
a recurring open development meeting with video conferencing. Open development meetings will be run by project 
administrators or senior reviewers.

User-facing support is primarily through answering questions on **Stack Overflow**, contributing to and maintaining a **Github 
Wiki page**, and promoting community dialogue with an associated **Gitter** channels. The purpose of Gitter is to move discussion 
from mailing lists to a more modern communication outlet.


### Development Policy
Generally, development on mature products will release minor/major versions, where minor versions are backwards compatible, 
and major versions can break ok API’s. Old API’s will be deprecated prior to removal.

New features which are experimental could be released in an **experimental** package, whereby all API’s in this package are 
subject to API changes without deprecation, and may change on a minor release (although this will be avoided if possible). 
Successful experimental features/APIs will eventually be migrated to other packages.

All code contributions to mature projects (Chisel, FIRRTL, etc.) must undergo a review process and pass continuous 
integration tests prior to merging into the master branch.

## Changing the Constitution
Changes to the constitution are proposed as pull requests against this document.
They are approved by 2/3 vote of the TAC as expressed by TAC members approving
the pull request on Github.

## TAC Voting
For events that require a vote of the TAC (eg. changing the constitution,
admitting new projects, admitting new members, selecting or changing TAC chair,
expelling projects, expelling members), votes may occur via TAC members approving
(or not approving) Github pull requests against this repository. Voting periods for
a given change are set by the chair to a length of time not less than 2 weeks.
Votes are tallied and if approved, pull requests are merged by the TAC Chair.

Because many decisions may be non-controversial or involve personnel decisions better
discussed in a meeting than via pull requests, votes *excluding changing the
constitution* may occur in official TAC meetings. These votes will be tallied by the
TAC chair, and if approved, reflected as pull requests by the chair against this
respository. The chair must mention in the pull request when the vote took place, and
another member of the TAC must approve the pull request for it to be merged.

## Code of Conduct (Contributors)

Adapted from https://github.com/YosysHQ/yosys, which is itself adapted from the Contributor Covenant, version 1.4, 
available at http://contributor-covenant.org/version/1/4/

### Our Pledge
In the interest of fostering an open and welcoming environment, we as contributors and administrators pledge to make 
participation in our project and our community a harassment-free experience for everyone, regardless of age, bodysize, 
disability, ethnicity, gender identity and expression, level of experience, nationality, personal appearance, race, 
religion, or sexual identity and orientation.

### Our Standards

Examples of behavior that contributes to creating a positive environment
include:

* Using welcoming and inclusive language
* Being respectful of differing viewpoints and experiences
* Gracefully accepting constructive criticism
* Focusing on what is best for the community
* Showing empathy towards other community members

Examples of unacceptable behavior by participants include:

* The use of sexualized language or imagery and unwelcome sexual attention or advances
* Trolling, insulting/derogatory comments, and personal or political attacks
* Public or private harassment
* Publishing others' private information, such as a physical or electronic address, without explicit permission
* Other conduct which could reasonably be considered inappropriate in a professional setting

### Our Responsibilities
Project administrators are responsible for clarifying the standards of acceptable behavior and are expected to take 
appropriate and fair corrective action in response to any instances of unacceptable behavior.

Project administrators have the right and responsibility to remove, edit, or reject comments, commits, code, wiki edits, 
issues, and other contributions that are not aligned to this Code of Conduct, or to ban temporarily or permanently any 
contributor for other behaviors that they deem inappropriate, threatening, offensive, or harmful.

### Scope
This Code of Conduct applies both within project spaces and in public spaces when an individual is representing the project 
or its community. Examples of representing a project or community include using an official project e-mail address, posting 
via an official social media account, or acting as an appointed representative at an online or offline event. 
Representation of a project may be further defined and clarified by project administrators.

### Enforcement
Instances of abusive, harassing, or otherwise unacceptable behavior may be reported by contacting the project team leader. 
All complaints will be reviewed and investigated and will result in a response that is deemed necessary and appropriate to 
the circumstances. The project team is obligated to maintain confidentiality with regard to the reporter of an incident. 
Further details of specific enforcement policies may be posted separately.

Project administrators who do not follow or enforce the Code of Conduct in good faith may face temporary or permanent 
repercussions as determined by other members of the project's leadership.

