# productionlanguagegenerator

Putting a Language Generator App Into Production

# Overview

Recently I completed an app, [srcflask](https://github.com/pwdel/srcflask), which uses GPT2 to generate text based upon a user input.

* This application leverages CPU, rather than GPU processing, which makes it slow. There is a need to leverage a tensorflow-gpu image rather than tensorflow-cpu.
* The container image size for this application is around 3GB, which is larger than the standard free tier Heroku app, so there is a need to upgrade to a production worthy-server, beyond Heroku Free.
* Heroku does not have any GPU options.

Basically, over the past few iterations of building applications and putting them into production, I have been using the Heroku free tier. This option is no longer viable and so there's a need to move into a machine-learning-grade production server.

# Production Server Options


# Subscriber Privileges on Microsoft

https://docs.microsoft.com/en-us/azure/cost-management-billing/manage/add-change-subscription-administrator
