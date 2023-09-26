# Sonar

================================================
Integrate Sonar server with Java Maven App
=================================================

-> Clone git repository 

-> Configure Sonar Properties under <properties/> tag in "pom.xml"

  <properties>
	<sonar.host.url>http://15.207.221.244:9000/</sonar.host.url>
	<sonar.login>admin</sonar.login>
	<sonar.password>admin</sonar.password>
  </properties>
	
-> Go to project pom.xml file location and execute below goal

			$ mvn sonar:sonar

-> After build success, goto sonar dashboard and verify the results

Note: Instead of username and pwd we can configure sonar token in pom.xml
