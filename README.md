# safetynet

# Project Safety Net

This safety net is intended to ease tension at the stress points in our civic infrastructure by finding alternative ways to address people’s needs through community organization. It is a global resource sharing network which will enable us to more efficiently get resources where they need to go, identify gaps in coverage and help get the people who want to help to work.

We are going to identify community leaders in cities across the world engaged in grass roots support efforts or leaders who would like to be engaged in such efforts. We’ll find people all over the globe who want to be helping. We’ll create a global resource sharing network and keep everyone aware of what each city needs. We’ll identify the gaps and we’ll fill them by shifting resources from places with surplus to places in need.

Each city has different pressure points so the specific projects will be determined by local community leaders and implemented through an international resource sharing network. As we find more people we’ll ask them what they need and what they have to give.


# Plan

* Establish a standard format for safety net projects (e.g. a JSON schema) and start adding data on a github repo.  Use pull requests for people to submit/review changes to the data.
* Build a website that displays that info with geolocation
* Extend the website to allow for data to be added by non-technical resources

# Design

As simple / cheaply scalable as possible:
* AWS hosting of docker containers that pull down from github on startup.  
* They store the data in JSON on local disk, with crontab to refresh from github.  
* Docker container also hosts some web container that renders the JSON into an interactive website

# Progress

A JSON schema is included in the repository along with an example - input welcome!
We need a web developer, who will decide on the web layer design and start coding
