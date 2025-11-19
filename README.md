# Hadoop Installation on Windows – Complete Step-by-Step Guide

## 1. Prerequisite
You must have **Java JDK 1.8** installed.

Check your Java version in CMD:
```bash
java -version
If Java is not installed, download JDK 1.8 from Oracle:

https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html

Download and extract Java into:
C:\Java\jdk1.8.0_181
(Do NOT install inside Program Files.)
## **2. Download Hadoop**

Download Hadoop 3.1.3 from:

https://hadoop.apache.org/releases.html

Extract it to:
C:\hadoop-3.1.3
Rename the folder to:
C:\hadoop
3. Configure System Environment Variables
Add User Variable

Variable name: HADOOP_HOME
Variable value: C:\hadoop

Add to System PATH

Edit Path → Add:
