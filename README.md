# microservice

Microservice projects.
################################################################################################################################
1) file-service.zip : 
This archive contains a file upload project. It will display content of text file < 10 mb and ptint their content in UI.

##############################################################################################################################


##################################################################################################################################
2) Load Balance pattern : 
This project will implement load balance pattern for microsevices. It contains a server and client part.


Server Implementation

a) loadbalancer.zip :
This archive contains a produser service implementation. This service will run in port (8090,9092 and 9999)

Run the server in ports 8090,9092 and 9999
URL Pattern = http://{host}:{port}/emps


Client


b) loadclient.zip :
This archive contains a consumer service implementation. 
This is a client implementation which is responsible for load balancing the loadbalancer service call.
Client will run on port 8888

URL Pattern = http://{host}:{port}/empcall

#################################################################################################################################


