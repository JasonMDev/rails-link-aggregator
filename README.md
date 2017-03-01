
# rails-link-aggregator
This a link aggregator site which similar to Reddit or Hacker News.
![Alt text](app/assets/images/FrontPage.jpg?raw=true "Hompage")

## Introduction
A user can sign up and submit a link. Comments can be made as well as vote up or down on link submissions.

This is based on the Reddit clone that [*Mackenzie Child: How To Build A Reddit Clone With Rails 4*](https://mackenziechild.me/12-in-12/1/) has build.

For more information, see [*Mackenzie Child*](https://mackenziechild.me/).

## Software Versions
*   Rails 5.0.0.1
*   Ruby 2.3.0
*   RVM 1.27.0

## Feautures
These are some of the feautures that have been added to the web page.
*   Scaffold of Links with "name" and "url" as fields
*   User Authentication with devise Gem
*   Front-end styling with the **bootstrap-sass** gem
*   Votable functionality with the **Acts_as_votable** gem
*   Simple form created using **simple_form** gem
*   Scaffold of Comment with "link_id", "body", and "user" as fields

## Further information
### Rails Commands
Commands used to create models and controllers.
[*link*](railsCommandInputs.md)

### Snapshots
These are snapshots of the various pages of the app.
[*link*](SNAPSHOTS.md)
