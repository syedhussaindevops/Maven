					Maven Build Tool
					================

What is Build

Build is a process of automating the packages(jar, war, ear)


About Maven 
===========
--> Maven is a popular build automation and project management tool used primarily for Java projects.
--> Developed by the Apache Software Foundation.
--> Maven is an open source build tool.
--> Maven is a platform independent. for Ex: U can install in windows,linux and mac
--> Maven is not an executable software(.exe), It is in the zip/tar.gz (download and extract)
--> if you want to download maven use this link below
   https://maven.apache.org/download.cgi  --> download maven zip file



What are the build tools
========================
+---------+----------------------+
| Language| Build Tools          |
+---------+----------------------+
| Java    | Ant, Maven, Gradle   |
| Python  | PyBuilder            |
| .NET    | MS Build, NAnt       |
| Ruby    | Rake                 |
| Go      | Go Build Tool        |
+---------+----------------------+


what is jar, war, ear 
=====================
jar stands for java archive
war stands for web archive
ear stands for enterprise archive

+----------------------+------------------------------------------+----------------------------------------------+----------------+
| Application Type     | Description                              | Contents                                     | Example        |
+----------------------+------------------------------------------+----------------------------------------------+----------------+
| Standalone (JAR)     | Runs on your local machine               | JAR contains  (.class files)                 | Calculator     |
|                      | (no internet required)                   |                                              |                |
|                      | Java code                                |                                              |                |
+----------------------+------------------------------------------+----------------------------------------------+----------------+
| Web (WAR)            | Runs on the internet using a browser     | WAR contains (JAR + HTML/CSS3/JS/Images)     | Redbus         |
|                      | Java code + Web content                  |                                              |                |
|                      | (HTML/CSS3/JS/Images)                    |                                              |                |
+----------------------+------------------------------------------+----------------------------------------------+----------------+
| Enterprise (EAR)     | Large and complex applications           | EAR contains (JAR + WAR +                    | Banking systems|
|                      | used by big organizations                | HTML/CSS3/JS/Images + Modules)               |                |
|                      | Java code + Web content +                |                                              |                |
|                      | Standalone & Web modules                 |                                              |                |
+----------------------+------------------------------------------+----------------------------------------------+----------------+

Maven Download Link:
https://maven.apache.org/download.cgi



Maven directory structure
=========================

bin ---> contains binary files [mvn, etc]

boot ---> contains jar files used at runtime 

conf ---> configuration files[settings.xml]

lib ---> contains library files[jars]


default xml file names for build scripts
=========================================

pom.xml										 ---> maven
build.xml 									 ---> ant
build.gradle[we can not use xml for gradle]  ---> gradle


