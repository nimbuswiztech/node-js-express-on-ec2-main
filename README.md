# node-js-express-on-ec2

# Code to prre installed

#!/bin/bash
sudo yun -y update
sudo amazon-linux-extras install epel
curl -sL https://rpm.nodesource.com/setup_6.x | sudo -E bash -
sudo yum install nodejs -y 
sudo npm install express
sudo yum -y install ruby
sudo yum -y Install wget
cd home/ec2-user
wget https://aws-codedeploy-us-east-1.s3.anazonaws.com/latest/Install
sudo chmod +x ./install
sudo ./install auto
