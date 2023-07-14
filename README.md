
## Requirements
All the requirements need to be installed to install this app on your local machine

- Docker
- Php 8.2
- Composer
- Nodejs/Npm

## Installing Docker
This app uses Docker. to install docker you need to go to this link [Docker](https://www.docker.com/)
After you install  you need to install Make File to make it easy to configure and install all needed on this app

## Install Make File in Windows
To install Make File in windows you need to open power shell and run this command: Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))

After you run the command in power shell just type choco install make to install makefile

to get all the details on how to install make file in windows just go on this website [Makefile Installation Windows Guide ](https://earthly.dev/blog/makefiles-on-windows/)

## Install Make File in Mac Os/Linux
to install Make file in MacOs and in Linux just open the terminal and type sudo apt install make

## How to install Docker Laravel Nginx
To install Docker Laravel Nginx just clone this app. after you clone this app you need to locate it on your terminal and type make setup to download and install all the need files in backend and the frontend. #### Just In Case that docker gets you error in the part in the front end. to fix just type cd frontend/react-app and type npm install


## Ports that has been used 
All ports that has been used in this app

- 8085 = nginx
- 8026 = react app/frontend
- 9000 = laravel app/backend

To see all the details about ports just type docker ps.

## Settings
All settings that has been used or modified in this app was

- make data = to create an table and run database seeder/run php artisan migrate and php artisan db:seed
- make fresh-data = to reset all the tables/run php artisan migrate:fresh
- make composer-update = to install/update all the dependencies of laravel
- make up = to up/run docker-compose file
- make stop = to stop docker-compose file
- make build = to build docker-compose file
- make setup = to run make buid make up and make composer-update at once




