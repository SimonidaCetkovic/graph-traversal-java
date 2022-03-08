
<h1>Graph Traversal exercise with setup via terminal</h1>

Prereqisites:
* JDK

Instructions:
1. Clone or download and unzip repository content

2. Download and copy testing framework jars to downloaded repository directory:

* https://search.maven.org/remotecontent?filepath=org/hamcrest/hamcrest-core/1.3/hamcrest-core-1.3.jar

* https://search.maven.org/remotecontent?filepath=junit/junit/4.13.2/junit-4.13.2.jar

3. Open command line and navigate to downloaded repository

4. Compile and run from command line:
* Unix:
  * Compile: ``` javac -classpath junit-4.13.2.jar *.java ```
  * Run: ``` java -cp junit-4.13.2.jar:hamcrest-core-1.3.jar:. org.junit.runner.JUnitCore GraphTest ```
