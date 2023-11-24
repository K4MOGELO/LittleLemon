# Welcome to Restaurant App

## Getting Started

### Prerequisites

* A Git repository
* VS Code
* Insomnia or Postman REST client
* Python 3.x
* Django
* MySQL

### Installation

1. Clone the Git repository
2. Create a virtual environment and activate it
3. Install Django and other dependencies
4. Configure the database connection
5. Run the Django development server

## Running Unit Tests

To run the unit tests, open a terminal window and navigate to the project directory. Then, run the following command:

python manage.py test tests/


## Testing the API

You can use the following API paths for testing purposes using Insomnia or Postman clients:

### User Authentication

* Create a new user:
    * POST: /auth/users/
* Login and get token:
    * POST: /api-token-auth/
* Login using JDOSER endpoint:
    * POST: /auth/token/login

### Menu Items

* Get all menu items:
    * GET: /restaurant/menu/
* Get a specific menu item:
    * GET: /restaurant/menu/{menuItemId}

### Table Booking

* Get all available tables:
    * GET: /restaurant/booking/tables/
* Book a table:
    * POST: /restaurant/booking/tables/
* Get a specific table booking:
    * GET: /restaurant/booking/tables/{bookingId}

## Static HTML Content

You can check that the web application serves static HTML content with images and styles by accessing the following path:

* GET: /restaurant

