# Demo-Transaction-API-JMeter

## Tools:
- JMeter

## Prerequisite:
- JDK
  
## How to run this project:
- Download JMeter from given link
```bash
https://jmeter.apache.org/download_jmeter.cgi
```
- Download "Demo Transaction API.jmx" file
- Run "ApacheJMeter.jar" from JMeter Bin folder
- Open downloaded "Demo Transaction API.jmx" file from JMeter then click on the "Start" button

## How to generate JMeter HTML Report:
- Download "Demo Transaction API.jmx" file
- Open Command Prompt(CMD) on your system
Example: cd C:\Users\Sayeed\Downloads
- Run command for generate HTML Report
```bash
jmeter -n -t <Downloaded .jmx File Path> -l <Auto Generated Test Log File> -e -o <Path to Output Folder>
```
Example: jmeter -n -t "C:\Users\NAYEEM\Desktop\Demo Transaction API.jmx" -l "C:\Users\NAYEEM\Desktop\Test Log File.csv" -e -o "C:\Users\NAYEEM\Desktop\HTML Report" 

## JMeter HTML Report Screenshot:
