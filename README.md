# AutoDKMH
*Command-line tool for automatically registering courses of VNU*
## Setup
Config account and course codes in ```src/config.properties``` follow template of ```src/config.properties.example```
  - ```usr``` - Student code
  - ```passwd``` - Password
  - ```course_codes``` - List of course codes, separated by dot characters (```.```)
  - ```course_codes``` - List of course codes, separated by dot characters (```.```)
  - ```options_classes``` - Be careful with this field. Use when a class have both theory and practice classes, 1 is first practice class, 2 is the second class, 0 is theory class. List of course codes, separated by dot characters (```.```)
  
  ```options_classes``` - Voi lop khong co lop thuc hanh thi la 0, lop thuc hanh so 1 la 1, lop thuc hanh so 2 la 2, ... (```.```)
## Run
Run with maven plugin

First install and run application: ```mvn install exec:java```
Compile new code and run applicaiotn: ```mvn compile exec:java```
Only run: ```mvn exec:java```
