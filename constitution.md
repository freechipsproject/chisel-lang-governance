# Chisel Working Group (CWG) Provisional Constitution

### Table of Contents
* [Relationship to CHIPS Alliance](#relationship-to-chips-alliance)
* [Mission Statement](#mission-statement)
* [Members](#members)
  * [Technical Advisory Committee](#technical-advisory-committee)
  * [Administrator](#administrator)
  * [Reviewers](#reviewers)
  * [Developers](#developers)
  * [Volunteers](#volunteers)
* [Collaboration Policy](#collaboration-policy)
  * [Communication Channels](#communication-channels)
  * [Development Policy](#development-policy)
* [Amending the Constitution](#amending-the-constitution)
* [TAC Voting](#tac-voting)
* [Code of Conduct](#code-of-conduct)
  
## Relationship to CHIPS Alliance

The Chisel Working Group is a member of CHIPS Alliance and subject to the bylaws established by
the CHIPS Alliance Board.

## Mission Statement
The Chisel ecosystem is a stable, user-friendly platform for production-quality RTL generator development, 
designed to support the needs of a variety of RTL development communities, including industry, academia, and individuals.

It includes support for the “Chisel stack”, including but not limited to FIRRTL, Testers, Chisel Utilities, documentation, 
and administrative work.

## Members
The Chisel self-governance consists of five types of members:
**Technical Advisory Committee members**, **administrators**, **reviewers**, **developers**,
and **volunteers**.

### Technical Advisory Committee
The role of Technical Advisory Committee (TAC) is to represent the interests of the
projects and members of the Chisel Working Group. This includes, but is not limited
to, facilitating communication and collaboration between members, as well as interfacing
with CHIPS Alliance on behalf of the Chisel community. Additionally, the TAC is
responsible for upholding the policies outlined in this document.

Other responsibilities include: admitting (and if necessary expelling) projects,
organizing community meetings/conferences, resolving disputes within and between projects,
allocating funds, clarifying procedures for each membership type, and publicizing
the Chisel community.

Projects are admitted (or expelled) by a 2/3 vote of the TAC, assuming a quorum is present.
A list of current projects is maintained in a document in this repository.

The TAC is made up of members of the community as well as one member appointed by
the CHIPS Alliance Board.
The members are listed by name and Github username in a document within
this repository. Membership changes are reflected by pull requests
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

#### Voting Procedure
Voting can only proceed if a quorum of 2/3 of all TAC members is established. An abstained vote counts towards quorum but not towards determining whether a motion passes or fails. Voting rules and procedure is enforced by the TAC Chair.
### Administrator
Consists of one lead and any number of additional administrators who direct a
given project and report progress to the TAC.
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

Reviewers strictly subsume Developers (e.g. they also have all the rights and responsibilities of Developers).

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
had over 10 reviews on a project, the individual can nominate themselves, or the community can nominate them, to become a Reviewer. A request is then sent to the administrators, who decide whether to add the individual as a Reviewer for that project.

Developers can contribute feedback by testing scheduled releases and fixes, and these members are critical to ensuring 
Chisel's backwards compatibility, as well as discovering bugs before a release. 

### Volunteers
Volunteers are people who want to contribute to a Chisel project, but do not commit to a regular contribution. They do 
not have voting rights, and no registration is required. Volunteers may attend development meetings. Volunteers may 
contribute through PRs to Chisel repositories, and are encouraged to review and comment but they cannot accept PR requests. It is hoped that volunteers will become developers.

## Collaboration Policy
The CWGs standard communication channels and development policies are outlined as follows, and will likely be adopted for other 
associated CHIPS Alliance working groups.

## Communication Channels
High level leadership directives will be published via mailing list, and minutes of these discussions will be posted on the 
Chisel website.

All technical development discussions will be done either on Github with Github issues, pull requests, and comments, or via 
a recurring open development meeting with video conferencing. Open development meetings will be run by project 
administrators or senior reviewers.

User-facing support is primarily through a commitment to answering questions, providing documentation, and promoting community dialogue via a variety of communication channels listed on the website.


### Development Policy
Generally, mature projects will release minor/major versions, where minor versions are backwards compatible, 
and major versions can break old APIs. Old APIs will be deprecated prior to removal.

New features which are experimental could be released in an **experimental** package, whereby all APIs in this package are 
subject to API changes without deprecation, and may change on a minor release (although this will be avoided if possible). 
Successful experimental features/APIs will eventually be migrated to other packages.

All code contributions to mature projects (Chisel, FIRRTL, etc.) must undergo a review process and pass rigorous testing prior to merging into the master branch.

## Amending the Constitution
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
discussed in a meeting than via pull requests, votes **excluding changing the
constitution** may occur in official TAC meetings. These votes will be tallied by the
TAC chair, and if approved, reflected as pull requests by the chair against this
respository. The chair must mention in the pull request when the vote took place, and
another member of the TAC must approve the pull request for it to be merged.

## Code of Conduct

As Chisel is a member of CHIPS Alliance, all Chisel activities and spaces are subject to
the [Linux Foundation Code of Conduct](https://lfprojects.org/policies/code-of-conduct/).
