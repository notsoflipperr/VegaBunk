
# VegaBunk - Java MySQL Application

A simple Attendance system using JavaFX frontend and MySQL database to store and display Student details marks and attendance.

### Additional feature - VegaBunk Calculator

A logic to get the 'No. of Missable classes' based on the desired Attendance percentage at the end of the year.


## Run Locally

Clone the project

```bash
  git clone https://github.com/md-nayaz-an/VegaBunk-Java-MySQL-Project.git
```

open the project folder in Java IDE.

**'JetBrains IntelliJ'** recommended.


Add Library to IDE classpath

- Right click on the project root folder in IntelliJ
- Click on 'open module settings'
- Click on Libraries
- Click the '+' icon
- Select the JDBC MySQL connector JAR in the '/Connector J 8.0/mysql-connector-java-8.0.29.jar' from root folder
- Click the '+' icon again
- Select 'all' the JavaFX modules JAR inside the '/openjfx-18.0.1_windows-x64_bin-sdk/javafx-sdk-18.0.1/lib/' from root folder

Add Run Configuration

- Click on Edit Configurations
- Click on '+' to add a new Configuration
- Select 'Application' and give a custom name
- select the main class from 'LoginPage (com.application.vegabunk)'
- Paste the following in the VM options
```bash
  --module-path "openjfx-18.0.1_windows-x64_bin-sdk\javafx-sdk-18.0.1\lib" --add-modules javafx.controls,javafx.fxml
```

Run the Application

- Click on the Run button in the IDE



## Tech Stack

**Client:** JavaFX

**Server:** Java

**Database:** MySQL
