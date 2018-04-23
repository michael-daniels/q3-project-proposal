# Q3 Project Proposal

## Project Description
A web app that helps people recover their lost pets.

## What problem does your project solve?
As it exists now, your main ways of recovering a lost pet are limited to lost and found sites or going out and posting up flyers in the physical world. The problems with these methods are that they reach a very small number of people.

## Who has this problem?
Anyone who has ever lost a pet, or anyone who has a pet given that their pet could eventually become lost.

## How will your project solve this problem?
My product will allow people to pay a fee to create a profile on my web app. They will then create a profile with all of the pertinent information on their missing pet.

Once they submit their profile and after payment, my web app will automatically create Internet ads (Google, Facebook, and Instagram) via third party APIs in a 2-3 mile radius around where the pet went missing. The money paid will be used to create ads in an effort to recover their pet. Google and Facebook both allow you to target geographical locations based on a specified radius and both have  APIs to allow for programmatic creation of ads from third party applications.

Once the ads are showing, people who actually live in the geographical location where the pet went missing will begin seeing them. The idea is that if someone has seen the pet, took it to the shelter, or even still has the pet, they can then click through the ad to the person's profile and give them that information.

It is basically taking the physical world flyer and bringing it online and automating it so that thousands a day in the location the pet actually went missing may see the alerts.


## What inputs does it need?
It will need a register form and a login form. The register form will send the API requests to the ad platforms. It will also need a comment system on the user's profile which will be full CRUD.

## What outputs does it produce?
It will output profile information, comments, and ad stats.

## What web API(s) will it use?
Google AdWords API, Facebook Marketing API

## What technologies do you plan to use?
HTML, CSS, Bootstrap, JavaScript, React, Redux, Node, Express, PostgreSQL, Knex

## Feature list
Profile registration
Automated ad creation
Ad stats dashboard (ad spend, clicks, views, etc)
Comment system on profile.
