# Linux Server Configuration Project

Technical information for Linux server configuration project.

## Technical Information

* IP Address: 142.93.28.26
* SSH port: 2200
* Web Application URL: http://142.93.28.26/

## Summary of software and configuration changes
1. Generate public/private rsa key pair.
2. Create project in [DigitalOcean](https://cloud.digitalocean.com) and setup Ubuntu machine.
3. Login to the remote machine using SSH and root user.
4. Upgrade software applications in the remote machine.
5. Change the SSH port from 22 to 2200.
6. Configure and activate the Firewall to allow only the ports 2200, 80, and 123.
7. Set timezone to UTC.
8. Create the user grader, configure SSH access, and add it to sudoers.
9. Install Apache web server.
10. Install and configure mod_wsgi.
11. Install and configure PostgreSQL.
12. Install pip.
13. Install and configure Git.
14. Clone the Item Catalog project from GitHub.
15. Install required packages.
16. Configure the VirtualHost for the application.
17. Disable the root login.
18. Run the application
