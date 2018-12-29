##Recognize Project
===========

## Freatures
- Social/private staff anniversaries & birthdays recognition
- Role-based employee recognitions & nominations
- 100+ gift cards & company-rewards management
- Flexible incentive program
- Seamless integrations & super customizable
- Painless user sync & configurable SSO
- Weekly platform updates & fixes

## Running server
+ Run server on port 500000
    
    ````
    bin/rails s -p50000
    bin/rails_ssl(SSL - need self signed cert and key in ~/.ssl)
    ````
    
## Running tests

    RAILS_ENV=test bin/rake recognize:init # first time only
    bin/rspec spec

##Dependencies
+ Qt(for capybara-webkit)
+ libv8
+ Mysql(v5.6.x)

## Mailcatcher(for local mail delivery)

    gem install mailcatcher
