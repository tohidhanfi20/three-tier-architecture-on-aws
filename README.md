# Three-tier-architecture-on-aws

<img width="1200" height="600" src=https://github.com/tohidhanfi20/three-tier-architecture-on-aws/blob/main/Images/1_lSIpD4-3C6F47yFBXjVvSQ.png>

Consider An E-commerce webiste or an online store

Lets Paint a Scenario

# Tier 1 = Presentation Tier
<img width="1200" height="600" src=https://github.com/tohidhanfi20/three-tier-architecture-on-aws/blob/main/Images/Presentation%20Tier.png>


# Tier 2 = Application Tier
<img width="1200" height="600" src=https://github.com/tohidhanfi20/three-tier-architecture-on-aws/blob/main/Images/Application%20Tier.png>


# Tier 3 = Data Tier
<img width="1200" height="600" src=https://github.com/tohidhanfi20/three-tier-architecture-on-aws/blob/main/Images/Data%20Tier.png>


# 3 Tier Architecture Diagram
<img width="1200" height="1000" src=https://github.com/tohidhanfi20/three-tier-architecture-on-aws/blob/main/Images/3%20Tier%20Architecture.png>

# Lets Start Our Project 

Step 1 - To Create our own VPC
        
        + Name your vpc i have named it (MyVpc)
        + IPv4 CIDR - 10.0.0.0/16
        + Create VPC
        + Edit VPC Settings
        + Enable DNS Hostname
        
Step 2 - To Create Internet Gateway

         + Name IGW
         + Create IGW
         + Attach IGW with Your VPC(MyVpc)
         
Step 3 - To Create Subnets (9)

 Web Tier Subnets
 
           +Name = Public-subnet-AZ1
           +Availability Zones = ap-south-1a
           +IP CIDR = 10.0.0.0/24

           +Name = Public-subnet-AZ2
           +Availabilty Zones = ap-south-1b
           +IP CIDR = 10.0.1.0/24

           +Name = Public-subnet-AZ3
           +Availability Zones = ap-south-1c
           +IP CIDR = 10.0.2.0/24
           
Application Tier Subnets

           +Name = app-subnet-AZ1
           +Availabilty Zones = ap-south-1a
           +IP CIDR = 10.0.3.0/24

           +Name = app-subnet-AZ2
           +Availabilty Zones = ap-south-1b
           +IP CIDR = 10.0.4.0/24
           
            +Name = app-subnet-AZ3
           +Availabilty Zones = ap-south-1c
           +IP CIDR = 10.0.5.0/24
           
Database Tier Subnets

           +Name = Private-db-subnet-AZ1
           +Availabilty Zones = ap-south-1a
           +IP CIDR = 10.0.6.0/24

           +Name = Private-db-subnet-AZ2
           +Availabilty Zones = ap-south-1b
           +IP CIDR = 10.0.7.0/24
           
            +Name = Private-db-subnet-AZ3
           +Availabilty Zones = ap-south-1c
           +IP CIDR = 10.0.8.0/24

Step 4 - Go to Subnets settings and Enable auto assign IPv4 address          

           






           










