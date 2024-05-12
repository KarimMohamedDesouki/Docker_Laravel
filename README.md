# Docker Laravel Authentication Labs at ITI

Welcome to the Docker Laravel Authentication Labs repository for your ITI course! This repository contains the solutions and resources for the Docker Laravel Authentication labs conducted during your course.

## Introduction

Docker is a platform for developing, shipping, and running applications in containers. Laravel is a powerful PHP web framework, and together with Docker, it provides a convenient way to manage dependencies and run Laravel applications in isolated environments. In this lab, we focus on setting up a Laravel application with Docker and implementing authentication functionality.

## Installation

To get started with Docker Laravel Authentication on your Windows machine, follow these steps:

1. **Install Docker Desktop**: Docker Desktop provides a Docker development environment for your Windows machine. You can download Docker Desktop from [here](https://www.docker.com/products/docker-desktop) and follow the installation instructions.

2. **Clone the Repository**: Clone the Docker Laravel Authentication repository to your local machine:

git clone https://github.com/your-username/docker-laravel-authentication.git


3. **Navigate to the Project Directory**: Change your current directory to the cloned repository:

**cd docker-laravel-authentication**


4. **Build and Run Docker Containers**: Run the following command to build and run the Docker containers:

**docker-compose up -d --build**


5. **Install Laravel Dependencies**: Once the Docker containers are up and running, install Laravel dependencies using Composer:

**docker-compose exec app composer install**


6. **Generate Application Key**: Generate the application key for Laravel:

**docker-compose exec app php artisan key:generate**


7. **Run Migrations**: Run database migrations to create the necessary tables:

**docker-compose exec app php artisan migrate**


Now you should have a Laravel application running with Docker and authentication functionality set up.

## Usage

Once the Docker containers are up and running, you can access the Laravel application in your web browser at http://localhost:8000. You can register new users, log in, log out, and access authenticated routes.

## Contributing

Contributions to this repository are welcome! If you find any issues, errors, or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. Feel free to use, modify, and distribute the code for educational purposes.


