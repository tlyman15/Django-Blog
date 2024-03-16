# Django Blog Project README

## Project Overview

This Django Blog project is a personal website designed to showcase proficiency across a full technical stack. It serves as a platform to demonstrate web development skills, including backend development with Django, frontend styling with Bootstrap, and deployment on a Linux (Ubuntu) server. This project is ideal for individuals looking to highlight their development capabilities and for educational purposes to understand the integration of various technologies in a real-world application.

## Technologies Used

- **Django**: A high-level Python Web framework that encourages rapid development and clean, pragmatic design.
- **Bootstrap**: An open-source toolkit for developing with HTML, CSS, and JS, enabling responsive, mobile-first projects on the web.
- **Ubuntu**: A Debian-based Linux operating system and distribution for desktops, servers, and more.
- **Bash**: A Unix shell and command language for the GNU Operating System.
- **Domain.com**: Used for registering a custom domain name for the project.
- **Linode**: A cloud hosting service for deploying the Django application.

## Features

- Responsive web design using Bootstrap.
- CRUD (Create, Read, Update, Delete) functionality for blog posts.
- User authentication and authorization for admin and regular users.
- Comments section for each blog post.
- Admin panel for easy management of blog posts and user comments.

## Prerequisites

Before you begin, ensure you have met the following requirements:
- A Linode account for deployment.
- A Domain.com account for domain registration.
- Ubuntu server (20.04 or newer) set up on Linode.
- Python 3.8 or newer installed on your Ubuntu server.

## Local Setup

1. **Clone the repository:**
   git clone https://github.com/yourusername/django-blog.git
   cd django-blog
2. **Set up a virtual environment:**
   python3 -m venv venv
   source venv/bin/activate
3. **Install required dependencies:**
   pip install -r requirements.txt
4. **Apply migrations:**
   python manage.py migrate
5. **Run the development server:**
   python manage.py runserver

Access the site at http://127.0.0.1:8000.

## Deployment

1. **Set up your Ubuntu server on Linode and SSH into your server.**
2. **Install necessary packages and setup the environment for Django on Ubuntu.**
3. **Transfer your project to the server using SCP or FTP.**
5. **Secure your domain with SSL using Let's Encrypt.**
6. **Update DNS settings on Domain.com to point to your Linode server.**

Refer to Linode and Django documentation for detailed steps on deployment.

## Contributing

Contributions to the Django Blog project are welcome. Please fork the repository and submit a pull request with your improvements.

## Contact

For any questions or suggestions, please contact Tolsonmlyman@gmail.com.
