# AutoDKMH
*Command-line tool for automatically registering courses of VNU*
## Setup
Config account and course codes in ```src/config.properties``` follow template of ```src/config.properties.example```
  - ```usr``` - Student code
  - ```passwd``` - Password
  - ```course_codes``` - List of course codes, separated by dot characters (```.```)
  - ```course_codes``` - List of course codes, separated by dot characters (```.```)
  - ```options_classes``` - Be careful with this field. Use when a class have both theory and practice classes, 1 is first practice class, 2 is the second class. List of course codes, separated by dot characters (```.```)
  
## Run
Run with maven plugin

First install and run application: ```mvn install exec:java```
Compile new code and run applicaiotn: ```mvn compile exec:java```
Only run: ```mvn exec:java```
