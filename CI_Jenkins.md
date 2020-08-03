# Continuous Integration & Jenkins


## Continuous Integration
**Automates code deployment**
- Automatically tests and integrates code once it
- Jenkins is automation tool to do this
- Automate all tests with Jenkins
	- Commit to github then Jenkins runs tests and does next steps
- Source(github) - build(jenkins) - test(jenkins) - production
- Continuous delivery - constantly creating and testing more code
- Continuous deployment - deploying code to customers 

## Before DevOps
**SDLC**
- Software development life cycle
- Steps of software being built - being used
- UAT(User acceptance testing)
- Performance testing(testing for how many users can de dealt with at once)
- Testing stages differ based on company and how testing is done
- May use CircleCI instead of Jenkins etc. 
- Getting product into production(deployment stage)
- Very slow - release of windows for example

## With DevOps
**Downloading software as a service**
- SAAS - e.g downloading teams instead of installing it

**Modern working methods**
- Where SDLC became defunct
- DevOps modernises old proccess with automation
- CICD 
- Make testing faster rather than doing it yourself
- Agile iterations
- Jenkins example of automation tool. On a daily basis can test if code works
	- Much safer in terms of security and not breaking software due to automated testing
- Once continuous integration working then move onto continous deployment - can deploy at any point

**Delivery vs deployment**
- C. Delivery is before code shown to customers, so code is ready to deployed
- C. Deployment is after code been shown to customers, exported to users

**Jenkins**
- Written in Java

**Jenksins private key**
- Jenkins will need a private key to access github
- Will only be able to access specific repositry

