# Answers for Question 4, 5 and 6

##### Prereq:

-JDK 1.8
-maven/mvn
-Jmeter 3.2

##### Structure:

-This framework can be run using,

```bash
mvn clean install
``` 


##### Configurations:

-If you need to change the hot, ports and other required parameters of the jmeter requests, you can configure them in the below location.

https://github.com/ushanib/Questions/tree/master/Questions4-5-6/QAPI/src/test/resources/user.properties

##Configurations of API1

#API1 Protocol

API1Protocol=http 


#Host name of the API1

API1host=passwordutility.net


#Port of the API1

API1port=80


#User ID of the API1

API1user_id=70f3fc6beac4412b82db266b4796b


#Password of API1

API1password=123456


##Configurations of API2

#API2 Protocol

API2Protocol=https


#Host name of the API2

API2host=od-api-demo.oxforddictionaries.com


#Port of the API2

API2port=443


#app id of api2

API2app_id=!no1me2digas!


#app key of api2

API2app_key=0clave42


-If you need to just run the jmeter, you can hardcode the values in jmeter script in Variables definition section
