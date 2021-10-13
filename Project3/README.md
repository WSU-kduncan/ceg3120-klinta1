# Project3

## Creating a VPC

1. Created a VPC: Virtual Private Could to allow the usage of network resources across multiple AWS instances
    ! [](Screenshots/VPC.png)

2. Created a Subnet: To create an IP range deticated to the VPC
    ! [](Screenshots/Subnet.png)

3. Created an internet gateway: To create remote access potential
    ! [](Screenshots/Gateway.png)

4. Created a route table: Creates a database that is used to keep track of all routed traffic
    ! [](Screenshots/RouteTable.png)

5. Created a security group: Allows SSH connection from certain IP address and/or ranges
    ! [](Screenshots/Securitygroup.png)

## EC2 Instance

1. Created a new AWI instance

2. Attached my VPC I created with the dropdown in the creation menu

3. I determined that auto assigning public IP addresses should be disabled so that I could later assign an elastic IP

4. I attached a volume going through the set up menue and using the add storage device option

5. I added a tag at the end of the process before review with the included add tag option

6. I associated my security group with the included drop down

7. I reserved an elastic IP after I ran the instance by selecting it and choosing the manage IP option in the actions drop down menue and creating a new elastic IP
    ! [](Screenshots/Instance.png)

