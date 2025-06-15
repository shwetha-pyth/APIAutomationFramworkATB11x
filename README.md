<h1 align="center">Hi 👋, I'm Shwetha H N</h1>
<h3 align="center">A passionate SDET engineer in india</h3>

- 🔭 I’m currently working on **Selenium Web Automation**

- 🌱 I’m currently learning **Data science, R programming, PowerBI**

- 👨‍💻 All of my projects are available at [https://github.com/shwetha-pyth/](https://github.com/shwetha-pyth/)

- 📫 How to reach me **shwethahn1992@gmail.com**

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://linkedin.com/in/www.linkedin.com/in/ shwethahn-validation-automation" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="www.linkedin.com/in/ shwethahn-validation-automation" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.arduino.cc/" target="_blank" rel="noreferrer"> <img src="https://cdn.worldvectorlogo.com/logos/arduino-1.svg" alt="arduino" width="40" height="40"/> </a> <a href="https://www.gnu.org/software/bash/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/gnu_bash/gnu_bash-icon.svg" alt="bash" width="40" height="40"/> </a> <a href="https://www.docker.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://www.java.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/> </a> <a href="https://www.jenkins.io" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/jenkins/jenkins-icon.svg" alt="jenkins" width="40" height="40"/> </a> <a href="https://www.linux.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://www.oracle.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/oracle/oracle-original.svg" alt="oracle" width="40" height="40"/> </a> <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> </a> <a href="https://postman.com" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" alt="postman" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://scikit-learn.org/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="scikit_learn" width="40" height="40"/> </a> <a href="https://seaborn.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="seaborn" width="40" height="40"/> </a> <a href="https://www.selenium.dev" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/detain/svg-logos/780f25886640cef088af994181646db2f6b1a3f8/svg/selenium-logo.svg" alt="selenium" width="40" height="40"/> </a> </p>


# API Automation RestAssured (in Java)

#### Author - Shwetha H N

API Automation Framework with the CRUD of Restful Booker.

`mvn test -Dsurefire.suiteXmlFiles=testng.xml`

<img width="1130" alt="Screenshot 2023-10-31 at 12 25 55 PM" src="https://github.com/PramodDutta/APIAutomationRestAssured/assets/1409610/69f398b3-8798-4fba-a091-3b1e321dcc7d">

## Tech Stack

1. Java ( JDK > 22)
2. Rest Assured
3. Apache POI, TestNG, Maven.
4. AssertJ (Advance assertions)
5. Jackson API and GSON
6. Log4j
7. Allure Report
8. Full Folder Structure(Hybrid) Framework.
9. Jenkins File

#### API Framework Important Components
![Screenshot 2024-06-29 at 12 44 29](https://github.com/PramodDutta/APIAutomationFramworkATB6x/assets/1409610/98bbc62d-7837-4bdc-900b-b214c675af6d)

#### Running via CI/CD
<img width="1262" alt="Screenshot 2023-10-31 at 12 26 07 PM" src="https://github.com/PramodDutta/APIAutomationRestAssured/assets/1409610/2d58bf82-0ffb-4fcb-a2d9-cf26920fa7b5">


Run

### Basic Create Test
* Install Maven
* add config to run the suite or testng

```<build>
    <plugins>
      <plugin>
        <groupId>org.apache.maven.plugins</groupId>
        <artifactId>maven-surefire-plugin</artifactId>
        <version>3.3.0</version>
        <configuration>
          <suiteXmlFiles>
            <suiteXmlFile>${suiteXmlFile}</suiteXmlFile>
          </suiteXmlFiles>
        </configuration>
      </plugin>
    </plugins>
  </build>
```
to **pom.xml**

```mvn clean test -DsuiteXmlFile=testng.xml ```


### Parallel Execution

To run tests in parallel, add the parallel attribute to your testng.xml file:

```<suite name="All Test Suite" parallel="methods" thread-count="2">```


### Integration Test (Create BookinG and Create Token , Update and Delete Booking)

``` mvn clean test -DsuiteXmlFile=testng-integration.xml```

### Allure Report Generated.


```allure serve allure-results/```

![image](https://github.com/PramodDutta/APIAutomationFramworkATB6x/assets/1409610/79ba2093-a1b7-4b36-ba16-9a6827af7afe)


Certainly! I'll guide you through the steps to install Allure and generate a report for a Java project using TestNG. Here's a step-by-step process:

#### 1. Install Allure

First, you need to install Allure Command Line Tool. If you're using a Mac, you can use the following Brew command:

```
brew install allure
```

For other operating systems, please refer to the official Allure documentation for installation instructions.

#### 2. Set up your Java project

Ensure you have a Java project set up with TestNG. If not, create a new Maven project and add the necessary dependencies.

#### 3. Add Allure dependencies

Add the following dependencies to your `pom.xml` file:

```xml
<dependency>
    <groupId>io.qameta.allure</groupId>
    <artifactId>allure-testng</artifactId>
    <version>2.13.0</version>
</dependency>
```

#### 4. Configure Allure in your project

Update the `<build>` section of your `pom.xml` to include the Allure Maven plugin:

```xml
<build>
    <plugins>
        <plugin>
            <groupId>io.qameta.allure</groupId>
            <artifactId>allure-maven</artifactId>
            <version>2.10.0</version>
            <configuration>
                <reportVersion>2.13.0</reportVersion>
            </configuration>
        </plugin>
    </plugins>
</build>
```


#### 5. Run your tests

Execute your TestNG tests using Maven:

```
mvn clean test
```

This will run your tests and generate the Allure results in the `target/allure-results` directory.

#### 6. Generate the Allure report

After running your tests, use the following command to generate the Allure report:

```
allure generate target/allure-results --clean -o allure-report
```

This command will create an `allure-report` folder containing the generated report.

#### 7. View the report

To view the report, you can use the following command:

```
allure open allure-report
```

This will start a local web server and open the report in your default browser.

#### Additional Tips

- You can use the `@Severity` annotation to indicate the importance of your tests.
- Allure supports attaching screenshots, which can be useful for UI tests.
- For more advanced configurations and features, refer to the official Allure documentation.

By following these steps, you should be able to successfully install Allure, run your TestNG tests, and generate a comprehensive Allure report for your Java project.


#### Try these Cases also

POSTMAN Assignments
 Assignment  1

Create the Collections for the This Test cases :

App - Restful Booker with(Auth)

1. Create a Booking, Update the Booking Name, Get the Booking by Id and verify.
2.  Create a Booking, Delete the Booking with Id and Verify using GET request that it should not exist.
3. Get an Existing Booking from Get All Bookings Ids , Update a Booking and Verify using GET by id.
4. Create a BOOKING, Delete It
5. Invalid Creation - enter a wrong payload or Wrong JSON.
6. Trying to Update on a Delete Id


Test for the Single Req
1. Response
2. Status Code
3. Headers

———

Create Collection
- [ ] RestfulBooker CRUD operation.
- [ ] Add from Snippets , Test cases
- [ ] Integration Scenarios (Hard Coded)
