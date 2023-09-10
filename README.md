# Theatre API Service

The project is designed to allow Theater visitors to make online reservations and choose the desired seats without physically entering the Theater.

## Project Description

- view available performances
- seat reservation
- view orders
- information about the performance

## Features

- JWT authenticated.
- Admin panel /admin/
- Documentation at /api/doc/swagger/

## Requirements

Make sure you have the following components installed on your computer:

- Python (version 3.11): [Link to Python installation instructions](https://www.python.org/downloads/)
- pip (Python package manager): Installed automatically with Python.
- Virtualenv (optional but recommended for environment isolation): Installed using pip.

## Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/Sebshe/theatre_API_service.git
   cd your-repository

2. Create and activate a virtual environment:
    ```bash
    python -m venv venv

    source venv/bin/activate # For Linux/Mac

    venv\Scripts\activate  # For Windows
   
3. Install project dependencies using pip:
    ```bash
   pip install -r requirements.txt

## How to run with Docker

Docker should be installed.

Create `.env` file with your variables.

```shell
docker-compose build
docker-compose up
