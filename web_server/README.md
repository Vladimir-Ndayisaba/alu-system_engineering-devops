# Web Server Project

## Description
This project is part of the ALU System Engineering and DevOps curriculum. It focuses on configuring and managing a web server using Nginx on an Ubuntu server.

The project covers basic web server administration, HTTP redirection, custom error pages, and file transfer using SSH.

## Project Tasks

### 0. Transfer a File to a Server
Created a Bash script that transfers a file from the local machine to a remote server using `scp` and an SSH private key.

### 1. Install Nginx Web Server
Created a script to install Nginx, configure the default homepage, and restart the web server.

### 2. Setup a Domain Name
Configured a domain name to point to the web server's public IP address.

**Domain:** vladimirndayisaba.tech

### 3. Redirection
Configured Nginx to redirect requests from `/redirect_me` to a specified YouTube URL using HTTP 301 redirection.

### 4. Not Found Page (404)
Configured a custom 404 error page displaying:

"Ceci n'est pas une page"

### 5. Design a Beautiful 404 Page
Created a custom HTML 404 error page with a responsive design, styling, and animations.

## Testing
The server can be tested using the following commands:

```bash
# Check the Nginx homepage
curl -I http://13.40.8.91

# Test the 404 error page
curl -i http://13.40.8.91/xyz

# Test the redirection
curl -I http://13.40.8.91/redirect_me
```

## Website
- Domain: https://vladimirndayisaba.tech
- Server IP: 13.40.8.91

## Author
Vladimir Ndayisaba


