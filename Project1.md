##__Project 1: WEB STACK IMPLEMENTATION (LAMP STACK) IN AWS__
1. LAMP (Linux, Apache, MySQL, PHP or Python, or Perl)
- Create Security Group in AWS and assigned it to  your instance
![A-SecurityGroup](https://user-images.githubusercontent.com/10111342/190007118-12fa9529-896e-441a-866d-6015ebe856b7.png)
- Instance -Project1 Created
![B-Instance](https://user-images.githubusercontent.com/10111342/190007812-f2b76efb-795e-46fc-8692-b08d91abdeb8.png)
- SSh connection info
![C-Connect to Instance](https://user-images.githubusercontent.com/10111342/190008177-a4d227db-0bd6-4bbd-8cd0-139670f60c79.png)
- Conected to the Instance via windows terminal
![D-Logged Into the Instance via Window terminal](https://user-images.githubusercontent.com/10111342/190008628-1e5fa322-d77f-46d5-b0cc-5fbfb7cb402e.png)
- Install Apache Server

Update a list of packages in package manager
```
`sudo apt update`

Run apache2 package installation


`sudo apt install apache2`

Verify that Apache2 is running as a service in our OS

`sudo systemctl status apache2`
```

![E-Apache Server Running](https://user-images.githubusercontent.com/10111342/190009050-da15b0d7-3dd1-4b53-a2c9-3312325a3df0.png)
*If server is not running due to server shutdown Use* 

`sudo systemctl enable apache2`
