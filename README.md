# CapstoneProjectLittleLemon

Capstone Little Lemon Project README

Welcome to the Capstone Little Lemon Project! This personal project is a testament to the culmination of my journey in mastering back-end development, particularly focusing on Django and the Django REST Framework. The goal of this project is to build a robust API for a fictional restaurant, Little Lemon, showcasing the practical application of the skills I've acquired.


Project Overview

The Capstone Little Lemon project is designed to simulate a real-world scenario where I'm tasked with developing the back-end for a restaurant's web service. This involves creating APIs for various functionalities such as browsing the menu and booking tables, all while ensuring the application's security and reliability through authentication and testing.
Prerequisites

For anyone interested in understanding or contributing to this project, here are some prerequisites:

    A good grasp of Python and Django
    Familiarity with Django REST Framework for building APIs
    Understanding of Git for version control
    Basic knowledge of database management, preferably MySQL

Project Structure

The project is divided into segments that represent key development milestones:
Setup and Initial Configuration

The project kicks off with setting up the Django environment, structuring the project, and preparing the static elements that will be served. This phase lays the foundation for the subsequent development work.
Building Core Functionalities

The core of the project revolves around developing the necessary APIs. This includes:

    Database Models: Designing and implementing models to represent the restaurant's menu items, bookings, and other relevant data.
    Menu and Booking APIs: Utilizing Django REST Framework to create endpoints for browsing the menu and managing table bookings.

Security Measures and Testing

With the core functionalities in place, the focus shifts to securing the application and ensuring its reliability:

    User Authentication: Implementing a system for user registration, login, and logout to secure access to certain functionalities, like table bookings.
    Testing: Employing unit tests and API testing (using tools like Insomnia REST client) to verify the functionality and security of the application.

Getting Started

To get this project up and running on your local machine, follow these steps:

Clone the repository:

    git clone <repository-url>

Set up a virtual environment and install dependencies:

    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    pip install -r requirements.txt

Initialize the database and run migrations:

    python manage.py makemigrations
    python manage.py migrate

Run the development server:

    python manage.py runserver

    Access the application by navigating to the localhost URL provided by the Django server.

Contributing

While this is a personal project, I'm open to contributions that can improve or add new features to the application. Feel free to fork the repository, make changes, and submit a pull request.
