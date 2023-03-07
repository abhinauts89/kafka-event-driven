# kafka-event-driven
This is sample kafka event driven application

docker compose up -d 

docker ps 
above command will tell container running 

http://localhost:8080/swagger-ui/#/user-controller

http://localhost:8081/swagger-ui/#/order-controller

if we update user from user controller then corresponding user is also updated in order controller that's how kafka is working 
