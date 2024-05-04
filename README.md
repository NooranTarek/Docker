# Docker
# Lab1
![1](https://miro.medium.com/v2/resize:fit:1200/1*XvJ0GDWOAEHNApZvw-dOVQ.png)

<html></br></html>


<html></br></html>

1. Create a container from hello-world image and set its name to first-container.
<html></br></html>

![image](https://github.com/NooranTarek/Docker/assets/102181986/a3c7cdb5-38a1-493f-ab98-7fb31cd538c5)

<html></br></html>

2. Create two containers from nginx image, run the first one in the foreground and the second one in the background.
![image](https://github.com/NooranTarek/Docker/assets/102181986/18b0d66e-8555-436d-85f7-7ff87bf2dd42)

<html></br></html>

![image](https://github.com/NooranTarek/Docker/assets/102181986/3b8e5dcc-37a0-43cd-936c-e30c736b8810)

<html></br></html>

![image](https://github.com/NooranTarek/Docker/assets/102181986/73cf7bb2-7c5d-47fe-8337-0fefceb113c2)

3.  • Download bitnami/laravel image (version 9.5.2) 
    • List all images 
    • Remove laravel image
    
    <html></br></html>
    
![image](https://github.com/NooranTarek/Docker/assets/102181986/21fa02ab-29b8-4049-a950-4e91befbce46)

    <html></br></html>
    
![image](https://github.com/NooranTarek/Docker/assets/102181986/de141f46-9740-47d8-a04b-c067ac2932e4)

    <html></br></html>
    
![image](https://github.com/NooranTarek/Docker/assets/102181986/8009a085-de3f-4984-ab90-c8d198743331)

    <html></br></html>
    
4. • Create a container from httpd image 
	  Map apache server running on the container to port 82 on 	your local machine
	  Check that it is working using your browser


       <html></br></html>

![image](https://github.com/NooranTarek/Docker/assets/102181986/99a33494-4ec7-4ada-903f-efd00f63ee3e)

       <html></br></html>
       
![image](https://github.com/NooranTarek/Docker/assets/102181986/99cb9a68-f0f1-44f0-a5f0-627d54c2e6da)

       <html></br></html>

5.  • Create file inside foreground container then list all files (use interactive mode)
    • Remove this container
    
       <html></br></html>
       
       ![image](https://github.com/NooranTarek/Docker/assets/102181986/ae36fad2-024c-4904-9f1f-ebd9d64cbe4e)

       <html></br></html>
       
       ![image](https://github.com/NooranTarek/Docker/assets/102181986/0f7c172f-d7df-4cb2-9279-70fce84d51cf)
       <html></br></html>
       
6. Print /etc/hosts file from background container (without interactive mode)

        <html></br></html>
	
![image](https://github.com/NooranTarek/Docker/assets/102181986/09fc426e-52d2-4fc5-b53b-63fa88909372)

       <html></br></html>
       
7. Create mysql container, map tmp directory (on your local machine) to /var/lib (on the container).
   
       <html></br></html>
       
       ![image](https://github.com/NooranTarek/Docker/assets/102181986/a9c9949f-afd0-41dc-8caf-5ab226d426bb)

       <html></br></html>
   
8. Create a volume lab1, start two containers from nginx image and mount this volume to /app, create a file from the first container on the path mapped to this volume and check that it exists on the second container.
    
          <html></br></html>
    
          ![image](https://github.com/NooranTarek/Docker/assets/102181986/2ec2c369-32b8-4d37-856a-78c8a16c09ce)

       <html></br></html>
       
   ![image](https://github.com/NooranTarek/Docker/assets/102181986/8179988c-eccc-4db7-8f30-afebeaad3560)

       <html></br></html>
       
   ![image](https://github.com/NooranTarek/Docker/assets/102181986/1d26d4ba-6670-4c5e-a921-52f51ddd9c41)

       <html></br></html>
       
   ![image](https://github.com/NooranTarek/Docker/assets/102181986/4fa68dda-6f16-41a0-a03c-c4715d5e39a1)

       <html></br></html>

