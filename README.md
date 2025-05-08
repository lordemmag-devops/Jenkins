### Using Jenkins on AWS

1. Create an EC2 instance on AWS and name it Jenkins
2. Copy the instance public IP address
3. ssh -i /path/to/secret/key/.pem ubuntu@IPAddress

# Install Java (Java is a prerequisite to run jenkins)
1. sudo apt update
2. sudo apt install openjdk-11-jre

# Install Jenkins
1. sudo apt install jenkins -y 

# Set up port
1. Go to the EC2 instance.
2. Select Security
3. Select groups
4. Click on add rule
5. Type port range eg"8080"

# Check if jenkins instance is accessible on your browser
'https://IPaddress:port number'
