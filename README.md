# CI Lab Project – Jenkins Continuous Integration on Linux

This project demonstrates the implementation of Continuous Integration (CI) using Jenkins on a Linux environment. The objective of this project is to automate the process of building and testing a Java application using Jenkins, GitHub, Maven, and JUnit. The setup ensures early detection of errors, automated testing, and improved software quality through continuous integration practices.

---

## Project Objectives

The main objectives of this project are:
* To understand and implement Continuous Integration concepts
* To install and configure Jenkins on a Linux system
* To integrate Jenkins with GitHub for automated builds
* To configure Jenkins Freestyle jobs and pipelines
* To automate build and test execution using Maven
* To generate build artifacts and test reports

---

## Tools and Technologies Used

* **Jenkins (LTS):** Automation server for CI/CD.
* **Git and GitHub:** Version control and repository hosting.
* **Java (OpenJDK 11):** Runtime environment for Jenkins and the application.
* **Maven:** Build automation tool for Java.
* **JUnit:** Testing framework for unit tests.
* **Python:** Used for auxiliary scripting.
* **Linux:** Ubuntu/Debian-based environment for hosting.

---

## Project Structure



```text
CILabProject/
├── src/
│   ├── main/java/com/muj/ci/Calculator.java
│   └── test/java/com/muj/ci/CalculatorTest.java
├── pom.xml
├── Jenkinsfile
├── docker/
│   └── Dockerfile
├── scripts/
│   ├── build.sh
│   ├── deploy.sh
│   └── hello.py
└── README.md
