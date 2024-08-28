# Django-Python-Machine-Test
# Project Name

A brief description of your project goes here. This could include the purpose of the project, its main features, and any relevant background information.

## Table of Contents

1. [Getting Started](#getting-started)
2. [Prerequisites](#prerequisites)
3. [Installation](#installation)
4. [Usage](#usage)
5. [API Endpoints](#api-endpoints)
6. [Screenshots](#screenshots)
7. [Contributing](#contributing)
8. [License](#license)
9. [Contact](#contact)

## Getting Started

These instructions will help you set up and run the project on your local machine for development and testing purposes.

## Prerequisites

- **Python 3.x**: Make sure you have Python 3 installed.
- **PostgreSQL**: The project uses PostgreSQL as the database. You need to have PostgreSQL installed and running on your machine.

### Postgres SQL 
Passwaord : Praful@01

### Superuser :- details
username : praful
Email address: prafulkd143@gmail.com
Password : Testapi@123


### user 1 :- user details for api
username : praful
Email address: prafulkd143@gmail.com
Password : Testapi@123


### user 2 :- details
username : admin
Email address: prafulkude369@gmail.com
Password : Testapi#369


### Database Configuration

Before running the project, ensure you have the correct PostgreSQL configuration:

- **Database Name**: `machine_test_db`
- **Username**: `praful_kude`
- **Password**: `praful123`

## Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Praful028/Django-Python-Machine-Test.git
   cd machine_test_api
   ```

## Run database migrations:

   ```
   python manage.py migrate
   ```

## Start the development server:
   ```
   python manage.py runserver
   ```

## Usage
To use the application, open your web browser and navigate to:
   ```
   http://127.0.0.1:8000/
   ```

# You can also use tools like Postman to interact with the API.
API Endpoints
Here are some API endpoints you can use to interact with the application:
### http://127.0.0.1:8000/api/clients/
### http://127.0.0.1:8000/api/projects/


List all clients:
GET /api/clients/

Create a new client:
POST /api/clients/

Retrieve a client:
GET /api/clients/:id

Update a client:
PUT /api/clients/:id

Delete a client:
DELETE /api/clients/:id

Create a new project:
POST /api/clients/:id/projects/

List all projects for the logged-in user:
GET /api/projects/

## Screenshots
Include screenshots to illustrate how to use the endpoints. Below are descriptions of the images you should upload:

List all clients:

![retriving client](https://github.com/user-attachments/assets/a211aea8-a347-407c-90b1-9c62bb3275b2)

Description: Screenshot of the Postman request for listing all clients using GET /clients/.
Create a new client:

![Screenshot 2024-08-28 201018](https://github.com/user-attachments/assets/6459b2e3-1c3c-420a-a227-952213ee64ad)

Description: Screenshot of the Postman request for creating a new client using POST /clients/.
Retrieve a client:

![retriving client by id](https://github.com/user-attachments/assets/1b1950c7-8ea0-404c-9481-820f6dac810d)


Description: Screenshot of the Postman request for updating a client using PUT/PATCH /clients/:id.
Update a client:

![update](https://github.com/user-attachments/assets/08042f7e-8a76-4f95-81b1-d0368c8c2319)


Description: Screenshot of the Postman request for updating a client using PUT/PATCH /clients/:id.
Delete a client:

![delete](https://github.com/user-attachments/assets/c4291f5c-dfb7-4a7e-868e-3108f016168f)


Description: Screenshot of the Postman request for deleting a client using DELETE /clients/:id.
Create a new project:

![project create](https://github.com/user-attachments/assets/b88e7eae-826c-41eb-a02c-9c7587c98e5c)


Description: Screenshot of the Postman request for creating a new project under a specific client using POST /clients/:id/projects/.
List all projects for logged-in user:

![all projects](https://github.com/user-attachments/assets/f60518b8-d19c-4fe5-ba21-99e4bdc7dd44)


Description: Screenshot of the Postman request for listing all projects for the logged-in user using GET /projects/.
To upload these photos:



## Contact
For any questions, please contact:

Email : prafulkude369@gmail.com
