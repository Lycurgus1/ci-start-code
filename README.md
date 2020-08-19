# Why should we use SSH with Github

## SSH Keys and github
**There are two methods to clone repositry**
- SSH AND HTTPS

**Types of repositry**
- We have two types of repos ```Public repo```, not secured
- Second is ```Private repo```, secured

## Generating SSH key
**Generate first on local system**
- Go to your user folder, then .ssh folder
- 'ssh-keygen -t rsa -b 4096 -C "max.palmer.official@outlook.com"'
	- Use email associated with github account
- Enter name then leave passphrase empty
- 'cat max.pub'
- Copy all of the encryted key

**Then copy the key to the specific repo on git-hub(ci-start-code)**
- Go to settings tab
- Deploy keys
- Name key and paste encrypted key into box
	- Name key with descriptive name - jenkins, docker, ansible etc. 
- Save key with green button. Dont click write access
- Will then receive email confirming key entered


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

**Jenkins private key**
- Jenkins will need a private key to access github
- Will only be able to access specific repositry
