# AutoDKMH
*Command-line tool for automatically registering courses of VNU*
## Setup
Config account and course codes in ```src/config.properties```
  - ```usr``` - Student code
  - ```passwd``` - Password
  - ```course_codes``` - List of course codes, separated by dot characters (```.```)
  - ```sleep_time``` - Sleep time between two adjacent executings
  
## Run
Run with maven plugin

First install and run application: ```mvn install exec:java```
Compile new code and run applicaiotn: ```mvn compile exec:java```
Only run: ```mvn exec:java```
