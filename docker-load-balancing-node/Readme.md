 # This is a sample of load balancing in Node.js:

 #### How to use :
 - Go to the project
 - Execute : docker build -t nodeapp:001 .
 - Run -p 5001:5000 --name helloworld -d nodeapp:001
 - Run -p 5002:5000 --name customized -e "name=aagam" -d nodeapp:001
 - Open a browser and tape : http://localhost:8080
 - It will redirect 60% traffic to app1 and 40% traffic to app2.
 - To quit, you can just CTRL + C in the terminal and it will stop the application and destroy the created containers.
 
