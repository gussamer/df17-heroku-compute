ffdc-df17-heroku-compute
===

This repo accompanies the Dreamforce '17 session **Beat Governor Limits By Taking Your Compute Processes to Heroku**.

It is optimized for development in VisualStudio Code.

Getting Started
---
See the [wiki](https://github.com/financialforcedev/df17-heroku-compute/wiki/Getting-Started) for deployment instructions.

Repository Structure
---
* This repository has 2 distinct components
    * [apex](/node): The Force.com component of the application
    * [node](/node): The Heroku component of the application
* This simplification allows developers to see and use the entire application in one place. However, for Production we would recommend you instead use small, single-purpose repositories.