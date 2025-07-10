🖥 Developer

Sanket Aswale
& Someshwar Hokarne


🔧Project Metadata

<groupId>com.company</groupId>
<artifactId>main.java</artifactId>
<version>1.0-SNAPSHOT</version>

•	Group ID: com.company

•	Artifact ID: main.java

•	Version: 1.0-SNAPSHOT

•	This identifies the project uniquely.

🛠️ Java Version & Encoding

<maven.compiler.release>24</maven.compiler.release>

<project.build.sourceEncoding>UTF-8</project.build.sourceEncoding>

•	Specifies Java release version 24 (very new).

•	Uses UTF-8 encoding for source files.


🏗️ Build Directories

    <sourceDirectory>...src\main\java</sourceDirectory>

     <outputDirectory>...target\classes</outputDirectory>

     <testSourceDirectory>...src\test\java</testSourceDirectory>
 
     <testOutputDirectory>...target\test-classes</testOutputDirectory>

🔌 Plugins in Use 

Plugin	Purpose

maven-compiler-plugin	Compiles Java source code

maven-jar-plugin	Creates .jar files

maven-surefire-plugin	Runs unit tests

maven-install-plugin	Installs package to local repo

maven-deploy-plugin	Deploys to remote repo

maven-javadoc-plugin	Generates Javadoc JARs

maven-source-plugin	Generates source JARs

maven-site-plugin	Generates project site and documentation

maven-antrun-plugin	Allows Ant tasks

maven-assembly-plugin	For creating distributions

maven-clean-plugin	Cleans build artifacts

maven-resources-plugin	Manages resource copying

🌐 Repositories

<url>https://repo.maven.apache.org/maven2</url>

📄 Main Class for Execution

<exec.mainClass>com.company.MainJava</exec.mainClass>

Specifies the entry point when using exec plugins or running the JAR.

📌 General Recommendations

✅ Functional for a Windows-based local Maven project.

⚠️ Avoid hardcoded paths – use Maven default structure or properties:
•	Replace C:\... with ${project.basedir}/src/main/java, etc.

🔼 Consider modularizing plugins under profiles if not always needed.

✅ Well-structured plugin management and executions.

📦 Packaging Result

Your final JAR will be named:

main.java-1.0-SNAPSHOT.jar

and located in:

target/

Dependencies
<!-- https://mvnrepository.com/artifact/org.postgresql/postgresql -->

<dependency>
  
    <groupId>org.postgresql</groupId>
    <artifactId>postgresql</artifactId>
    <version>42.7.7</version>
    <scope>runtime</scope>
</dependency>

