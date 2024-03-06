# MAVEN

Maven Commands
Let’s look into some popular and must know maven commands. We will use a sample Maven project to showcase the command output.

1. mvn clean
This command cleans the maven project by deleting the target directory.

2. mvn compiler:compile
This command compiles the java source classes of the maven project.

3. mvn package
This command builds the maven project and packages them into a JAR, WAR, etc.

4. mvn install
This command builds the maven project and installs the project files (JAR, WAR, pom.xml, etc) to the local repository.

5. mvn deploy
This command is used to deploy the artifact to the remote repository.

6. mvn validate
This command validates the maven project that everything is correct and all the necessary information is available.

7. mvn dependency:tree
This command generates the dependency tree of the maven project.

8. mvn archetype:generate
Maven archetypes is a maven project templating toolkit. We can use this command to generate a skeleton maven project of different types, 
such as JAR, web application, maven site, etc.

9. mvn site:site
This command generates a site for the project. You will notice a “site” directory in the target after executing this command. There will be multiple HTML files inside the site directory that provides information related to the project.

10. mvn test
This command is used to run the test cases of the project using the maven-surefire-plugin.

11. mvn compile
It’s used to compile the source Java classes of the project.

12. mvn verify
This command build the project, runs all the test cases and run any checks on the results of the integration tests to ensure quality criteria are met.





