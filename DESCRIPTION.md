# Product Description

VoteSnap will be developed in stages.

## Stage 1
Objectives:
* Drive voter turnout in local elections
* Make voting easier
* Lessen the gap between organizations and their followers.

Methodology:
* Provide a centralized dashboard (`Election Dashboard`) where the user can see all the elections that are coming up for them and associated information.
  - Who is in the election?
  - When is the election taking place?
  - Where is the election taking place?
  - What are the contentious topics in the election?
  - **What are various organizations, like ACLU or NRA, saying about the candidates?**

User flow:
* The user navigates to `https://votesnap.org` and signs up. They enter their email, password, and home address.
* The user is shown an election dashboard on the left and a communication dashboard on the right.
  - _election dashboard:_ details every election that the user can participate in, with metadata.
  - _communication dashboard:_ messages put out by mission-driven organizations (including campaigns) that the user follows.
    * Also visible is a 'who to follow' page, which lists various mission-driven organizations (like NRA, NYC Democrats, or ACLU) that the user can follow. If the user follows such an organization, the candidates that organization endorses on VoteSnap will be visible next to that politician on the voter dashboard and their communications (or targeted communications) will appear in the communication dashboard.

Election dashboard:
* _The user sees every election they are eligible to participate in._ (This information is currently hard to get; bring out the vote!)
* The user can click on any election to receive an expanded view.
* For each election, the following information is available:
  - candidates
  - parties
  - endorsements
  - platforms
  - voting station
  - date of election
  - pictures of the candidates

Communication dashboard:
* _The communication dashboard shows the user what the organizations they follow want them to know to stay informed and involved. These messages are put out by the organizations themselves on VoteSnap and can be targeted (to a zip code or district). **Users only see communications from organizations they follow.**_
* Users can, on an opt-in basis, choose to receive email notifications from certain organizations or on messages of a certain type.
* Communications could include PSAs, protest announcements, or general messages.
* Communications would show up in a chronological order on the user's communication dashboard.
* Users can give emoji-reactions to announcements (like GitHub or Slack), but cannot post comments. Direct messages _can_ be sent to organizations.

 Other miscellanous features **in stage 1**:
 * Users can vote in elections on the platform itself, though these results are not shared publicly and the user's decision is only shown to the user
 * Users can go to an organization's page and see all the candidates they endorsed and any communications.
 * For transparency, targeted communications can be viewed by anyone on an organization's page if the user goes to the 'all messages' tab and not the 'most relevant messages' tab.
 
 ## Future stages
 The following features/ideas could be implemented in later stages:
 * polling (by organizations)
 * direct back-and-forth communication between organizations (which includes legislators) and users.
