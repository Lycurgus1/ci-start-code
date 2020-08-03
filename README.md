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
