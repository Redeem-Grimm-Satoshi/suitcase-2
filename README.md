# odk-x-suitcase

This project is actively maintained

You can find the developer wiki (including release notes) and issues tracker are located under the ODK-X Tool Suite project.

Getting started with Setting up Your Environment
Install Maven and Ant onto your system.
Run ant in the dependencies folder.
From the root directory (with the pom.xml), run: mvn clean package
A new folder, target, will be created with the resulting jar file.

By default, the pom.xml skips the tests.

The tests can be run by passing the test arguments via the command line. Replace the values in the example below with the appropriate server url, app id, etc. :

mvn clean package -DskipTests=false -Dtest.aggUrl=http://127.0.0.1 -Dtest.appId=default
-Dtest.absolutePathOfTestFiles=testfiles<file.separator> -Dtest.batchSize=1000 -Dtest.userName= -Dtest.password=

How to contribute
If you are new to ODK-X, you can check out the documentation:
https://docs.odk-x.org
Once you’re up and running, you can choose an issue to start working on from here: 

https://github.com/odk-x/tool-suite-X/issues
Issues tagged as good first issue should be a good place to start.

Pull requests are welcome, though please submit them against the development branch. We prefer verbose descriptions of the change you are submitting. If you are fixing a bug please provide steps to reproduce it or a link to a an issue that provides that information. If you are submitting a new feature please provide a description of the need or a link to a forum discussion about it.

Links for users
This document is aimed at helping developers and technical contributors. For information on how to get started as a user of ODK-X, see our online documentation, or to learn more about the Open Data Kit project, visit https://odk-x.org.
