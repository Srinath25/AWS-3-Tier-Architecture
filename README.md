💻 Architecting a Scalable and Resilient Three-Tier Application on AWS.

I recently completed a project where I designed and implemented a robust three-tier architecture on AWS for a React.js frontend, Node.js backend, and Aurora MySQL database.

Key components of the architecture:
Public-facing Application Load Balancer: Distributes incoming traffic across multiple web tier EC2 instances.
Web Tier (Nginx): Serves static React.js content and proxies API requests to the application tier.
Application Tier (Node.js): Handles business logic, interacts with the Aurora MySQL database, and communicates with the web tier.
Internal Application Load Balancer: Distributes traffic across multiple application tier instances.
Aurora MySQL Database: Stores and manages application data with high availability and durability.

To ensure high availability and scalability:
Load Balancing: Implemented at both web and application tiers using Application Load Balancers.
Health Checks: Regularly monitor the health of EC2 instances and automatically remove unhealthy instances from the load balancer.
Autoscaling Groups: Dynamically adjust the number of EC2 instances based on load to maintain optimal performance.
By carefully architecting and implementing this solution, we achieved a highly available, scalable, and performant application capable of handling increased traffic and data volumes.

![Screenshot (3166)](https://github.com/user-attachments/assets/9a1b5539-68f8-483c-9f5b-214434ea053c)
![Screenshot (3167)](https://github.com/user-attachments/assets/cba87b14-c3f9-4b13-823e-222af922a0f5)
![Screenshot (3168)](https://github.com/user-attachments/assets/a8c1732f-1e75-4145-acdd-12cd4443a896)
![Screenshot (3169)](https://github.com/user-attachments/assets/b0f0f2ab-610d-4d45-9410-5128649d414d)
![Screenshot (3170)](https://github.com/user-attachments/assets/3ef2b4b4-cb61-4bd2-bffd-a3c1a41114d7)
![Screenshot (3171)](https://github.com/user-attachments/assets/333890f6-e13b-4f43-8793-cdcdd32db4d4)
![Screenshot (3172)](https://github.com/user-attachments/assets/b8bf6ad8-de1e-4dfa-b1f9-8ca8133f8f4e)
![Screenshot (3174)](https://github.com/user-attachments/assets/78a682ef-3a95-4e5b-9003-03344c64ff67)
![Screenshot (3173)](https://github.com/user-attachments/assets/cda3435c-44ca-47b5-8d6d-0071ff7b0cce)
![Screenshot (3175)](https://github.com/user-attachments/assets/b74b742c-a773-4765-b867-56ebd8ea86de)
![Screenshot (3176)](https://github.com/user-attachments/assets/46b0a455-8d19-43bb-9374-d942a7311c73)
![Screenshot (3177)](https://github.com/user-attachments/assets/a112db1b-979d-4116-8ef4-22303b1af377)
![Screenshot (3178)](https://github.com/user-attachments/assets/2e08b9aa-dcc7-4233-8a0a-5585c45af0f7)
![Screenshot (3179)](https://github.com/user-attachments/assets/7dfe7395-58f5-49d8-9b9c-8ba2548638be)
![Screenshot (3181)](https://github.com/user-attachments/assets/ddd280ef-5750-4a9f-9e35-196e80c95355)

https://github.com/user-attachments/assets/62025e1e-61a9-4c0e-bcaf-a147bbdb6067
