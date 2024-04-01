# Food Delivery Application

This is a food delivery application built using Python and Django. It allows users to order food from various restaurants and provides a personalized dashboard for restaurant owners to manage their menus and view statistics.

## Features

- Users can browse restaurants and their menus.
- Users can place orders online.
- Restaurant owners can manage their menus through a personalized dashboard.
- Restaurant owners can view statistics related to their orders and revenue.
- Integrated online payment gateway for secure transactions.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/swapnildubey29/Food-Delivery-Application.git
    ```

2. Navigate to the project directory:

    ```bash
    cd food-delivery-app
    ```

3. Create a virtual environment:

    ```bash
    python -m venv venv
    ```

4. Activate the virtual environment:

    - On Windows:

    ```bash
    venv\Scripts\activate
    ```

    - On macOS and Linux:

    ```bash
    source venv/bin/activate
    ```

5. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

6. Apply database migrations:

    ```bash
    python manage.py migrate
    ```

7. Create a superuser (for accessing admin panel):

    ```bash
    python manage.py createsuperuser
    ```

8. Run the development server:

    ```bash
    python manage.py runserver
    ```

9. Open your browser and go to `http://127.0.0.1:8000/` to access the application.

## Usage

- As a user, you can browse restaurants, view menus, and place orders.
- As a restaurant owner, you can log in to your dashboard to manage your menu and view statistics.

## Contributing

Contributions are welcome! If you want to contribute to this project, feel free to fork the repository and submit a pull request with your changes.

