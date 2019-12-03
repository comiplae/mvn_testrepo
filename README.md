How to download and build the project.
===============================
1. Downloading the project:
- Open command line (e.g. Git Bash)
- Go to directory where you want store source code of project (using cd command)
- Clone repository using the following command:
		git clone https://github.com/comiplae/mvn_testrepo.git mvn_testrepo

2. Building the project:
- Go to project directory where pom.xml is located.
- Open command line and type:
		mvn package

To run project use following command: 
		java -cp target/mvn_testrepo-1.0-SNAPSHOT.jar me.comiplae.mvntestrepo.App
