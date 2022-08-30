# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_
* First set up a github account then download the github desktop app and log in using your newly created credentials, \
* Clone the company repo
* Any modified files should be commited with relevant documentation, 
* Install WSL, if this is the firs time follow the steps on microsoft official doc, if not try it any way but in case this fails i would suggest doing a fresh installation of windows so any registry or file that may interfere with the installation gets erased, took me a day and a half trying workarounds but in the end the fresh installation did the trick
* Install docker this step comes after WSL because you need this to run docker
* run the following command to verify the installation docker-compose -v
* then on the root folder, the one you clone from company repo run this command docker-compose up to start the environment