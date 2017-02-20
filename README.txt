NAME          : Gurnoor Singh Bhatia
Student ID    : 011490284
email         : gurnoor.bhatia@sjsu.edu

How to Run:


OPTION 1 (using files committed in Canvas):

1) ‘cd’ into a directory where you wish to generate project. Then run the following commands:
1.1) 
mvn archetype:generate -DgroupId=com.gurnoors.cmpe202.uml -DartifactId=Spring3Example -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false
1.2)
mvn eclipse:eclipse

2) Place files in project
2.1) Copy App.java, Greeter.java and HelloUser.java into <projDir>/src/main/java/com/gurnoors/core/
2.2) Copy beans.xml into <projDir>/src/main/resources/
2.3) Copy pom.xml into <projDir>/

3) Import "existing maven project" in Eclipse. 

4) Run the "com.gurnoors.core.App" class.


OPTION 2 (using git):
1) clone (or download zip) the repo: https://github.com/gurnoors/Spring3Example
2) Import "existing maven project" in Eclipse.
3) Run the "com.gurnoors.core.App" class.