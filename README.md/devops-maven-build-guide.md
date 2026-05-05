# 🚀 Maven Build Tool Guide (Beginner Friendly)

## 👨‍💻 Author
Syed Hussain  
DevOps Learner | 4 Years Experience in Healthcare IT  

---

## 📌 Table of Contents
- What is Build
- About Maven
- Build Tools
- JAR vs WAR vs EAR
- Maven Directory Structure
- Build Script Files

---

## 📌 What is Build

Build is a process of automating the creation of packages like:
- JAR
- WAR
- EAR

---

## 📌 About Maven

- Maven is a **build automation and project management tool** used for Java projects  
- Developed by the **Apache Software Foundation**  
- Open-source tool  
- Platform independent (Windows, Linux, Mac)  
- Maven is not an executable (.exe), it comes as **.zip / .tar.gz**  
- Download and extract to use  

🔗 Download Maven:  
https://maven.apache.org/download.cgi  

---

## 📌 Build Tools by Language

| Language | Build Tools |
|---------|------------|
| Java    | Ant, Maven, Gradle |
| Python  | PyBuilder |
| .NET    | MS Build, NAnt |
| Ruby    | Rake |
| Go      | Go Build Tool |

---

## 📌 JAR vs WAR vs EAR

| Application Type | Description | Contents | Example |
|-----------------|------------|----------|--------|
| Standalone (JAR) | Runs on local machine (no internet required) | .class files | Calculator |
| Web (WAR) | Runs on browser (internet required) | JAR + HTML/CSS/JS/Images | Redbus |
| Enterprise (EAR) | Large-scale applications used by organizations | JAR + WAR + Modules | Banking Systems |

---

## 📌 Maven Directory Structure

| Folder | Description |
|--------|------------|
| bin | Contains mvn commands |
| boot | Contains runtime jar files |
| conf | Configuration files (settings.xml) |
| lib | Library jar files |

---

## 📌 Build Script File Names

| Tool | File Name |
|------|----------|
| Maven | pom.xml |
| Ant | build.xml |
| Gradle | build.gradle |

---

## 📌 Key Notes

- JAR → Java Archive (Standalone Application)  
- WAR → Web Archive (Web Application)  
- EAR → Enterprise Archive (Large Applications)  

---

## 🚀 Next Steps (Coming Soon)

- Sample `pom.xml`
- Maven Lifecycle Commands
- Real-time project example
- CI/CD integration using Jenkins

---

⭐ If you found this useful, feel free to star the repo!
