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

Description: Screenshot of the Postman request for listing all clients using GET /clients/.
Create a new client:

Description: Screenshot of the Postman request for creating a new client using POST /clients/.
Retrieve a client:

Description: Screenshot of the Postman request for retrieving a client using GET /clients/:id.
Update a client:

Description: Screenshot of the Postman request for updating a client using PUT/PATCH /clients/:id.
Delete a client:

Description: Screenshot of the Postman request for deleting a client using DELETE /clients/:id.
Create a new project:

Description: Screenshot of the Postman request for creating a new project under a specific client using POST /clients/:id/projects/.
List all projects for logged-in user:

Description: Screenshot of the Postman request for listing all projects for the logged-in user using GET /projects/.
To upload these photos:


## Contact
For any questions, please contact:

Email : prafulkude369@gmail.com
