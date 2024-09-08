ON AWS GUI
CREATE A VPC -> ASSIGN IP 
CREATE AN INTERNET GATEWAY ->ATTACHED TO NEWLY CREATED VPC
CREATE TWO SUBNETS ->PUBLIC->PRIVATE
CREATE TWO ROUTES FROM ROUTE TABLE PUBLIC & PRIVATE -> SUBNET ASSOCIATION FOR BOTH 
ADD INTERNET GATEWAY TO PUBLUC ROUTE ->ROUTE->EDIT ->INTERNET GATEWAY
Create a new instance for public webserver by selecting vpc created by us ->assign new security group select public subnet
Edit inbound rules-> all icmp4 & Http
Launch instance in cli and use below commands to set up web server
  yum install httpd
    2  cd
    3  cd /bar/www/html
    4  cd /var/www/html
    5  echo "this is new preactuse" > index.html
    6  cd
    7  systemctl start httpd
    8  systemctl enable httpd
Now for private ->create an private instance -> copy ke.pem file content -> add to key.pem follow below commands
vim key.pem
   11  ssh -i "new-jenkins.pem" ec2-user@30.0.1.27
   12  ssh -i "key.pem" ec2-user@30.0.1.27
   13  chmod 400 key.pem
   14  ssh -i "key.pem" ec2-user@30.0.1.27
   15  history

Now you are inside pruvate instance which does not have Internet access so now we need to create an NAT Gateway
Create a NAT-Gateway
Go to ROute tables->Private Route -> Routes ->Add ->Nat Gateway -0.0..0.
Now you have susccessfully setuped connection for private server try pinging ->ping www.google.com

