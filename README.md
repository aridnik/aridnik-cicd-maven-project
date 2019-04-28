# Aridnik-CICD-Maven-Project
#### Sample Java Code with Maven
 
## Commands
```sh

# Clone cicd-terraform repository
$ git clone https://github.com/aridnik/cicd-maven-project.git
$ cd cicd-maven-project

# Set New Version for Snapshots
$ mvn versions:set -DnewVersion=YYYY.MM.BUILD_NUMBER-SNAPSHOT

# Set New Version for Release
$ mvn versions:set -DnewVersion=YYYY.MM

# Code Build
$ mvn clean install 

# Deploy artifacts to Nexus
$ mvn deploy
```
