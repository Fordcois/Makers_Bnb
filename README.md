# Makers BnB - Airbnb Clone

## Project Overview

Makers BnB is a web application inspired by Airbnb, allowing users to register accounts, list their spaces for rent, browse other users' listed spaces, and request to stay at those spaces. Makers BnB is built using a stack of modern web development technologies, including Python, Flask, HTML templates, and PostgreSQL for data storage.

## Key Features

### User Registration and Log-ins

Makers BnB offers a simple and intuitive registration process, enabling users to create accounts. A registered account is required to post and book spaces.

### Space Listing and Management

Users can easily list their spaces for rent, providing details like space name, description, and price per night.

### Browsing and Booking

- **Browse Spaces:** Users can explore spaces listed by other users, offering access to a variety of accommodation options.

- **Booking Requests:** Users can request to stay at a space on available dates, creating booking requests.

- **User Authentication:** User login is required to create booking requests and manage spaces.

### Space Owner Actions

- **Approvals and Denials:** Space owners can view pending booking requests and choose to approve or deny them.

### User Dashboard

- **Submitted Booking Requests:** Users can view the status of their submitted booking requests, whether they are pending, approved, or denied.

## Technology Stack

- **Backend:** Makers BnB is powered by Python and utilizes the Flask web framework.
- **Database:** PostgreSQL is used for storing user information, space details, and booking requests.
- **HTML Templates:** Web pages are rendered using HTML templates.

## Project Installation & Set-up
Before proceeding, ensure you have an active [PostgreSQL server](https://www.postgresql.org/) to store the information.

### Clone Repo
Clone the Repository  Clone the repository to your local machine:  
```shell 
git clone <repository_url> 
cd <repository_name>
```

### Install Dependencies and Set up the Virtual Environment
Install dependencies using pipenv:
```
pipenv install
```
Activate the virtual environment:
```
pipenv shell
```

### Set up Test and Development Databases
Create databases for testing and development:
```shell
createdb MAKERSBNB 
createdb MAKERSBNB_test
```

### Run Tests
Run tests with extra logging:
```pytest -sv```

### Run the Web Server
Start the Flask web server:
```python app.py```

### Visit the Application
Open your browser and navigate to [http://localhost:5001](http://localhost:5001) to access the application.
