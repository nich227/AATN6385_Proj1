# CS 6385 - Project 1

## How to run
NOTE: This assumes you already have Maven and Java 11 installed. If not, follow instructions on how to install the software.
1.	Create a new folder, with a descriptive name (e.g. ```project-1```) and go into this folder.
2.	Copy the ```pom.xml``` file to the root of this folder.
3.	Create new folders within this folder, with this structure: ```src/main/kotlin/com/cs6385```
4.	Copy the ```NetworkTopGen.kt``` and ```Runner.kt``` files to this folder.
5.	Go back to the root project-1 folder and run 
mvn clean package 
in the terminal.
6.	A new target folder should have been created after the build is successful. Go into this target folder and run in the terminal: 
```bash 
java -jar project1-1.0-SNAPSHOT.jar <k-value>
```

