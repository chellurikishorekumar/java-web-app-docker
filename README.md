Lets create an EC2 Instance

![AWS instance creation1](https://github.com/user-attachments/assets/01f984e4-8ec6-41d8-8505-6315e76f6b12)

![AWS instance created](https://github.com/user-attachments/assets/29408be0-f2c8-42af-a07a-aec2627ab0e5)

![AWS Page](https://github.com/user-attachments/assets/56ea3679-71c9-4b11-98e7-a1e9952d51cb)

![AWS instance Launch](https://github.com/user-attachments/assets/f659abde-faca-4c4d-b479-60f435096070)

Now install Docker and start the docker service

![ssh to D_S](https://github.com/user-attachments/assets/b96c23a1-b266-4a87-aede-d5d6823b1681)

Install git and clone the repository url to the docker server:

![install git](https://github.com/user-attachments/assets/cb713412-0f09-4c8e-9253-ac7a3c3ae9f3)

![git clone repo](https://github.com/user-attachments/assets/25fb96d4-63b4-4dd2-a063-0881f0329b3c)

![goto to repository](https://github.com/user-attachments/assets/9c22f1a1-8b7c-4e37-9d1e-0678c952fa38)

Installing java 17 for our java web application:

![install java](https://github.com/user-attachments/assets/9b5d4c21-5ce1-4495-8d17-833394f25131)

Now Install Maven build tool.

![maven installation](https://github.com/user-attachments/assets/d0f60745-72e2-4fe0-a9d0-28bedcc20d3f)

![maven installation-1](https://github.com/user-attachments/assets/78d761ca-6333-434e-97ab-571f3bb8cfab)

Here it will takes our project's Java source code, compiles it, tests it and converts it into an executable Java program

![mvn clean package](https://github.com/user-attachments/assets/147517bf-9e5a-49c0-bf01-a6467558e3df)

![Build success](https://github.com/user-attachments/assets/ff537108-83d5-4684-a102-f988f4cb75b0)

Build's the docker image for java web application and tag it as kishorech48/java-web-app:latest, in the current directory (.).

![docker image build](https://github.com/user-attachments/assets/a6889da2-a805-4922-a1ec-386933accca0)

Run the container:

![docker container was created](https://github.com/user-attachments/assets/8fef57d0-3f8a-46e5-a3d0-4db8b23e9470)

It uploads (pushes) your locally built Docker image  (kishorech48/java-web-app:latest) to a Docker registry, typically Docker Hub

![docker hub](https://github.com/user-attachments/assets/d078441d-f687-42aa-854b-59bbb6cb05a3)

![docker cont image pushed to docker hub](https://github.com/user-attachments/assets/e97396d6-3ac4-4e5b-83b4-204a41a66ffc)

Attach security group to access the application by using custom tcp, port 7070 as shown in below.

![security group](https://github.com/user-attachments/assets/fa2fd168-6966-43f0-8004-7a85deeb3b27)

![application was not accessible due to permission issue](https://github.com/user-attachments/assets/50ecba35-e5aa-48f1-a26c-60bcc86ec1fd)

Java web application might be deployed under /java-web-app instead of /.

![application was accessible and running](https://github.com/user-attachments/assets/3a76715b-4f24-4067-87ba-ef09c43f09f2)
