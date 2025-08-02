#  Setup Guide: CI/CD Pipeline - Jenkins + Maven + Tomcat

---

##  Prerequisites

- Java 8+ installed
- Maven installed and configured
- Jenkins installed
- Tomcat 9 installed

---

##  Jenkins Job Configuration

1. Go to Jenkins → New Item → Pipeline
2. Set GitHub repo URL
3. Use `Jenkinsfile` from this repo
4. Add tool `MAVEN3` under Jenkins Global Tools

---

##  Folder Used in Jenkinsfile

```groovy
git 'https://github.com/Rahul9041/cicd-maven-tomcat-pipeline.git'

