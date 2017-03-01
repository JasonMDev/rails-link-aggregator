
# rails-link-aggregator

This a link aggregator site which similar to Reddit or Hacker News.

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

## Snapshots
Here are some snapshots of specific pages of the wbesite.
### Homepage
This is the landing page.
![Alt text](app/assets/images/FrontPage.jpg?raw=true "Hompage")
### Submit Individual Link Page
Here you can submit a link.
![Alt text](app/assets/images/SubmitLink.jpg?raw=true "Submit Individual Link Page")
### Individual Link Page.
Here you can view a link that has been submitted, and also delete the comment if the user has created it.
![Alt text](app/assets/images/IndLinkPage.jpg?raw=true "Individual Link Page")
### View and Edit Link
Users that  created the link also have acess to a "destroy" button
![Alt text](app/assets/images/LinkEdit.jpg?raw=true "Edit Link Page")
### Sign-up Page
This is the user sign-up page.
![Alt text](app/assets/images/SignUp.jpg?raw=true "Sign-up Page")
### Sign-in Page
This is the user sign-in page.
![Alt text](app/assets/images/SignIn.jpg?raw=true "Sign-in Page")
### User Update Page
This is the user update page.
![Alt text](app/assets/images/EditAcc.jpg?raw=true "User Update Page")
