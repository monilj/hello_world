# hello_world
This is hello world program to github
This is Monil Joshi wants to contribute in Github

# egnikai-test #

This is maven based UI test automation suite which uses testNg and selenide  framework and extent Report for reporting.

# Tech Stack # 
Java 8

selenide 4.11.1

TestNg 6.10

# Setup #
Install chrome.

Install java

Create a folder in local for cloning. 
Open terminal and go to perticular project folder.
Clone repositary 
`git clone https://bitbucket.org/siddhag/egnikai-test`

Check pom.xml whether it contains following dependency added : 

selenide 4.11.1

TestNg 6.10

mysql-connector-java 8.0.12

super-csv 2.1.0

commons-csv 1.5

poi 3.16

poi-ooxml 3.15

extentreports 3.1.5


### Run through IDE ###

Go to Run Menu > Edit configuration

Select TestNg configuration

Select Test kind as __Method__

Mention class and method name

In VM Option send parameter 

`-Devn=environment_name(dev/qa) -DsuiteXmlFile=CandidateTestng.xml -Dbrowser=chrome`
Select JRE 

Apply changes


### Run through terminal ###

Open terminal

Go to directory in egnikai-test where pom.xml file is present

Hit following command

`mvn clean install -DsuiteXmlFile=CandidateTestng.xml -Denv=environment_nameQA`



