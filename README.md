
# rails-link-aggregator

This a link aggregator site which similar to Reddit or Hacker News. 

## Introduction
A user can sign up and submit a link. Comments can be made as well as vote up or down on link submissions.

This is based on the Reddit clone that [*Mackenzie Child: How To Build A Reddit Clone With Rails 4*](https://mackenziechild.me/12-in-12/1/) has build. 

For more information, see [*Mackenzie Child*](https://mackenziechild.me/).


## Feautures
### User Authentication with devise Gem
### Front-end styling with the bootstrap-sass gem
### Votable functionality with the Acts_as_votable gem
### Scaffold Links name url
### Scaffold Comment link_id body user

## Snapshots
### Homepage
### Individual Link Page
### User Pages
#### Signup Page
#### Sign-in Page
#### User Update Page
### Comment

## TODO:
get commands
#### Commands
'''
$ rails g scaffold Comment link_id:integer:index body:text user:references --skip-stylesheets
'''
