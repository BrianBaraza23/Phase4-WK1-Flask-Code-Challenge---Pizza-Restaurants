# Phase4-WK1-Flask Code Challenge - Pizza Restaurants

**Date Created:** 23 September 2023

**Assignment:** Flask Code Challenge - Pizza Restaurants

## Description

This Flask application is designed to manage a Pizza Restaurant domain. It provides endpoints to interact with restaurants and pizzas, allowing you to view, create, and delete restaurant-pizza relationships. The application enforces validations for data integrity and responds with JSON data in the specified format.

## Author

Brian Baraza

## Features

As a user, this application offers the following capabilities:

- View a list of restaurants with their IDs, names, and addresses.
- View the details of a specific restaurant, including its pizzas.
- Delete a restaurant, which also deletes associated restaurant-pizza relationships.
- View a list of pizzas with their IDs, names, and ingredients.
- Create a new restaurant-pizza relationship by providing the price, pizza ID, and restaurant ID.


## Requirements

Before using this application, ensure you have the following:

- A computer running one of the following operating systems: Windows 7+, Linux, Mac OS.
- Python installed on your system.
- Flask and Flask extensions installed (`pip install Flask flask-restful flask-sqlalchemy`).
- A database set up using SQLite 
- Postman or a similar tool for testing the API endpoints.


**Note:** To run the database server, execute the following command in your terminal within the project directory:

```bash
npx json-server --watch db.json --port 5555
```

This command will start a JSON server to simulate database functionality.

### Technologies Used

- Python
- Flask
- SQLite (for database)
- Flask-RESTful (for building REST APIs)

## Usage

1. Clone this repository to your local machine.

2. Install the required Python packages using `pip install Flask flask-restful flask-sqlalchemy`.

3. Start the Flask application by running `python your_app_name.py` in your terminal.

4. Use Postman or a similar tool to test the following endpoints:

   - GET `/restaurants`: View a list of restaurants.
   - GET `/restaurants/:id`: View details of a specific restaurant by replacing `:id` with the desired restaurant's ID.
   - DELETE `/restaurants/:id`: Delete a restaurant by its ID.
   - GET `/pizzas`: View a list of pizzas.
   - POST `/restaurant_pizzas`: Create a new restaurant-pizza relationship by providing the required data in the request body.

## Contact

For any inquiries or assistance, please reach out to:

- barazabrian87@gmail.com

## License

This project is licensed under the MIT License.# Phase4-WK1-Flask-Code-Challenge---Pizza-Restaurants
