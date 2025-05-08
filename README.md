### Using Jenkins on AWS

1. Create an EC2 instance on AWS and name it Jenkins
2. Copy the instance public IP address
3. ssh -i /path/to/secret/key/.pem ubuntu@IPAddress

# Install Java (Java is a prerequisite to run jenkins)
1. sudo apt update
2. sudo apt install openjdk-11-jre
