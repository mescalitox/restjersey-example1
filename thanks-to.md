#from 
*	xml [http://www.journaldev.com/9170/restful-web-services-tutorial-in-java-using-jersey-and-resteasy]
* 	json [https://www.mkyong.com/webservices/jax-rs/json-example-with-jersey-jackson/]

#creation eclipse

new web dynamic project, puis maven > convertir en projet maven

#test avec soapUI ou outildev firefox

*	add

	*	url : [http://localhost:8080/resteasy-example1/employee/add]
	*	header : content-type : application/xml
	*	body : 
```xml
<?xml version="1.0" encoding="UTF-8" standalone="yes"?>
<employee>
	<id>1</id>
	<name>Toto</name>
	<salary>100.00</salary>
</employee>
```

*	getDummy : 

	*	url : [http://localhost:8080/resteasy-example1/employee/99/getDummy]

*	getAll :
 
	*	url : [http://localhost:8080/resteasy-example1/employee/getAll]
	
#Json
*	*	add

	*	url : [http://localhost:8080/resteasy-example1/employeeJson/add]
	*	header : content-type : application/json
	*	body : 
```json
	{"name":"Dummy","salary":8976.55,"id":1}
```	
