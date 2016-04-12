# interfacing

maven structure:
baseline pom: 3rd party baseline pom
parent pom: versioning all sub projects
java_api pom: project specific pom (versions of sofware used should be define in the baseline)

This repository should hold all serverside api implementation aswell as clientside api interfaces

Serverside:
project: java_api
description: Spring boot project incl. REST (Swagger.io)

usage:
fork on github
git clone https://github.com/<<"your user">>/interfacing.git

cd interfacing

mvn clean install

<Eclipse> maven update project (resolve dependencies)
<Netbonen> ?

main class:
src/main/java/uk/co/cyberbliss/App.java

run as application

todo:
refactor all cyberbliss into nl.project_x
