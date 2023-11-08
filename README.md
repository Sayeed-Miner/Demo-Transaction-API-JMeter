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
- Run command for generate HTML Report
```bash
jmeter -n -t <Downloaded .jmx File Path> -l <Auto Generated Test Log File> -e -o <Path to Output Folder>
```
Example
```bash
jmeter -n -t "C:\Users\Sayeed\Downloads\Demo Transaction API.jmx" -l "C:\Users\Sayeed\Downloads\Test Log File.csv" -e -o "C:\Sayeed\Sayeed\Downloads\HTML Report"
```

## JMeter HTML Report Screenshot:
