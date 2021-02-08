# Demo application 
This project used to demonstrate usage of other services registered with Spring could eureka-discovery-server

### To Build project:
run mvn clean install

### Steps:
* To check the service getting registered with service discovery, we need to run service discovery on our machine, You can find project in my repo [eureka-service-discovery](https://github.com/santoshmv121/eureka-discovery-server)
* Run another sample service and register with service discovery , You can find a sample project in my repo [sample service](https://github.com/santoshmv121/sample-service)
* Step 1: Launch service discovery
* Step 2: Update the service name in "virtualHostName" property of EurekaClientApplication Class (used as "eureka-service")
* Step 3: Launch eureka-discovery-client 
* Step 4: Check the instance name of sample service ("eureka-service") on service discovery dashboard http://localhost:8761/

