# WordPress Docker Project

## What is this Project?
This project helps you set up your own WordPress website using **Docker**. WordPress is a popular tool for creating websites and blogs, and Docker makes it super easy to get everything running on your computer without needing to manually install complicated software.

---

## What You’ll Need
Before you start, make sure you have these installed on your computer:
1. **Docker**: A tool to run applications in containers.
2. **Docker Compose**: A tool to help run multiple containers together (like WordPress and its database).

If you don’t have them installed, ask your teacher or follow [this guide for Docker installation](https://docs.docker.com/get-docker/).

---

## How to Use This Project
1. **Download the Project Files**  
   Clone this project from GitHub:
   ```bash
   git clone https://github.com/EliseHill/Elise.git
   cd wordpress_docker
step 2. 
Start the WordPress Website
Run this command in the project folder:
docker-compose up -d
- this will download everything you need and start your WordPress Website
- The -d makes it run in the backgorund

  step 3. Visit your website
  - Open your web browser and go to:
     http://localhost:8080
  - Follow the on-screen instructions to set up your WordPress site. You'll choose a name
  - for your site, a username, and a password.
 
  - Step 4. How to stop the website
  -  When youre done, you can stop the WordPress site by running:
     docker-compose down
    - this stops the containers but doesnt delete your work
 
Step 5. Troubleshooting
- Here are some tips if things dont work as expected:
-   I dont see the website at http://localhost:8080.
-     Make sure Docker is running on your computer.
-     Check if the containers are running:
-       docker ps
-   How do i see what went wrong?
-     Check the logs with:
-       docker-compose logs

-   What did you learn?
  By completeing this project, you learned:
  1. How to use Docker and Docker Compose
  2. How to run a WordPress website locally
  3. Basic Troubleshooting tips for working with Docker
 
  - 
