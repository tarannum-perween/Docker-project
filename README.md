# Docker-project
This is my docker project. It can create a fully functional wordpress website with just a single click with have its own database.


You can use Docker Compose to easily run WordPress in an isolated environment built with Docker containers. This quick-start guide demonstrates how to use Compose to set up and run WordPress. Before starting, make sure you have Compose installed.

Define the project
Create an empty project directory.

we can name the directory something easy for you to remember. This directory is the context for your application image. The directory should only contain resources to build that image.

This project directory contains a docker-compose.yml file which is complete in itself for a good starter wordpress project.

Tip: You can use either a .yml or .yaml extension for this file. They both work.

Change into your project directory.

For example, if you named your directory my_wordpress:

cd my_wordpress/
Create a docker-compose.yml file that starts your WordPress blog and a separate MySQL instance with a volume mount for data persistence:

now use command docker-compose up to run this yml file .
with this single command all your databases along with your worpress website launches.
