# MortgageAdviseJmeterProject

Assignment 3: Jmeter performance testing.There are 2 files as mentioned below:
   1)API_testing.dmx: This will consist of the Test Plan for https://reqres.in API
   2)Demo.jmx: This will consist of the Test plan for the Demo website

****PreRequisites:*****
Install apache jmeter
Import the jmx files in the Jmeter

****Steps to run the code:****
1) Click on run button after iumporting the jmx files.

******To Generate the report files follow the below command*****
JTL Reports:
jmeter -n -t API_Testing.jmx -l API_Report.jtl
HTML Reports:
./jmeter -g API_Report.jtl -o API_Report.html
