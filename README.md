
# rails-link-aggregator

This a link aggregator site which similar to Reddit or Hacker News. 

## Introduction
A user can sign up and submit a link. Comments can be made as well as vote up or down on link submissions.

This is based on the Reddit clone that [*Mackenzie Child: How To Build A Reddit Clone With Rails 4*](https://mackenziechild.me/12-in-12/1/) has build. 

For more information, see [*Mackenzie Child*](https://mackenziechild.me/).

## Software Versions
### Rails 5.0.0.1
### Ruby 2.3.0
### RVM 1.27.0

## Feautures
### User Authentication with devise Gem
### Front-end styling with the bootstrap-sass gem
### Votable functionality with the Acts_as_votable gem
### Simple form created using simple_form gem
### Scaffold Links name url
### Scaffold Comment link_id body user

## Snapshots
### Homepage
### Individual Link Page
### User Pages
#### Signup Page
#### Sign-in Page
#### User Update Page
### Comments
#### Show one with and without "destroy"

## TODO:
get commands
#### Commands
'''
$ rails g scaffold Comment link_id:integer:index body:text user:references --skip-stylesheets

$ rails g migration add_name_to_users name:string

'''
