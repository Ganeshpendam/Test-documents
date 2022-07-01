
# Selenium Test Automation Boilerplate
Ready-to-use UI Test Automation Architecture using Java and Selenium WebDriver.
## Languages and Frameworks
The project uses the following:
- *[Java 11](https://openjdk.java.net/projects/jdk/11/)* as the programming language.
- *[Selenium WebDriver](https://www.selenium.dev/)* as the web browser automation framework using the Java binding.
- *[WebDriverManager](https://bonigarcia.dev/webdrivermanager/)* as the browser driver management library.
- *[Univocity Parsers](https://www.univocity.com/pages/univocity_parsers_tutorial)* to parse and handle CSV files.
- *[TestNG](https://testng.org/doc/)* as the testing framework.
- *[AssertJ](https://assertj.github.io/doc/)* as the assertion library.
- *[Lombok](https://projectlombok.org/)* to generate getters.
- *[Owner](http://owner.aeonbits.org/)* to minimize the code to handle properties file.
- *[Extent Reports](https://www.extentreports.com/)* as the test reporting strategy.
- *[Selenium Shutterbug](https://github.com/assertthat/selenium-shutterbug)* for capturing screenshots.
- *[Gradle](https://gradle.org/)* as the Java build tool.
- *[IntelliJ IDEA](https://www.jetbrains.com/idea/)* as the IDE.
## Project Structure
```bash
selenium-test-automation-boilerplate/
├─ .github/
│  ├─ workflows/
│  │  ├─ test-execution.yml
├─ gradle/
│  ├─ wrapper/
│  │  ├─ gradle-wrapper.jar
│  │  ├─ gradle-wrapper.properties
├─ report/
│  ├─ screenshot/
├─ script/
│  ├─ install_chrome.sh
├─ src/
│  ├─ main/
│  │  ├─ java/
│  │  │  ├─ io/
│  │  │  │  ├─ github/
│  │  │  │  │  ├─ tahanima/
│  │  │  │  │  │  ├─ config/
│  │  │  │  │  │  │  ├─ Configuration.java
│  │  │  │  │  │  │  ├─ ConfigurationManager.java
│  │  │  │  │  │  │  ├─ package-info.java
│  │  │  │  │  │  ├─ data/
│  │  │  │  │  │  │  ├─ login/
│  │  │  │  │  │  │  │  ├─ LoginData.java
│  │  │  │  │  │  │  ├─ BaseData.java
│  │  │  │  │  │  │  ├─ package-info.java
│  │  │  │  │  │  ├─ driver/
│  │  │  │  │  │  │  ├─ BrowserFactory.java
│  │  │  │  │  │  │  ├─ DriverManager.java
│  │  │  │  │  │  │  ├─ package-info.java
│  │  │  │  │  │  ├─ page/
│  │  │  │  │  │  │  ├─ login/
│  │  │  │  │  │  │  │  ├─ LoginPage.java
│  │  │  │  │  │  │  ├─ product/
│  │  │  │  │  │  │  │  ├─ ProductsPage.java
│  │  │  │  │  │  │  ├─ BasePage.java
│  │  │  │  │  │  │  ├─ BasePageFactory.java
│  │  │  │  │  │  │  ├─ package-info.java.java
│  │  │  │  │  │  ├─ report/
│  │  │  │  │  │  │  ├─ ReportManager.java
│  │  │  │  │  │  │  ├─ package-info.java
│  │  ├─ resources/
│  │  │  ├─ general.properties
│  ├─ test/
│  │  ├─ java/
│  │  │  ├─ io/
│  │  │  │  ├─ github/
│  │  │  │  │  ├─ tahanima/
│  │  │  │  │  │  ├─ login/
│  │  │  │  │  │  │  ├─ LoginTest.java
│  │  │  │  │  │  ├─ util/
│  │  │  │  │  │  │  ├─ DataProviderUtil.java
│  │  │  │  │  │  ├─ BaseTest.java
│  │  │  │  │  │  ├─ TestListener.java
0 comments on commit cac78c2
@Ganeshpendam
 
Leave a comment
No file chosen
Attach files by dragging & dropping, selecting or pasting them.
 You’re not receiving notifications from this thread.
Footer
© 2022 GitHub, Inc.
Footer navigation
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pricing
API
Training
Blog
About
