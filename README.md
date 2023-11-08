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

## JMeter HTML Report:
https://precious-crepe-05e071.netlify.app/

## JMeter HTML Report Screenshots:
![Home Page](https://github.com/Sayeed-Miner/Demo-Transaction-API-JMeter/assets/52811620/22eb695c-3c90-41a6-bbe3-e1aeb6e3e929)
![Statistics](https://github.com/Sayeed-Miner/Demo-Transaction-API-JMeter/assets/52811620/065e6cd6-008d-4a1d-83c2-4163baa50278)
![Response Times Over Time](https://github.com/Sayeed-Miner/Demo-Transaction-API-JMeter/assets/52811620/c8717642-dde2-4192-86bb-73dc0fa229af)
![Response Time Percentiles](https://github.com/Sayeed-Miner/Demo-Transaction-API-JMeter/assets/52811620/b1fe5d83-8d48-4bc7-9450-13fe0426e85e)
![Response Time Overview](https://github.com/Sayeed-Miner/Demo-Transaction-API-JMeter/assets/52811620/9c35d0af-f35c-454a-810a-02b019369ae6)
