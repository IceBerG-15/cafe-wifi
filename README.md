# Cafe WiFi

This is a simple Flask web application that allows users to submit information about cafes, including their location, open and close times, and ratings for coffee, WiFi, and power outlets. The data is stored in a CSV file and can be viewed in a table format on a separate page.

### Live Link: https://rapid-disk-8387.ploomberapp.io

## Features

- Submit new cafe information through a form.
- Store cafe data in a CSV file.
- Display the list of cafes with their details.

## Technologies Used

- Flask
- Flask-Bootstrap
- Flask-WTF
- WTForms
- Gunicorn

## Requirements

- Python 3.x
- The packages listed in `requirements.txt`

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/cafe-collector.git
    cd cafe-collector
    ```

2. Create and activate a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Running the Application

1. Start the Flask application:
    ```bash
    python main.py
    ```

2. Open your web browser and go to `http://127.0.0.1:5000/` to view the home page.

## Application Routes

- Home: `http://127.0.0.1:5000/`
  - Displays the home page.

- Add Cafe: `http://127.0.0.1:5000/add`
  - Contains a form to submit new cafe information.

- View Cafes: `http://127.0.0.1:5000/cafes`
  - Displays a table with the list of all cafes and their details.

## Form Fields

- **Cafe name**: The name of the cafe.
- **Location URL**: A URL to the cafe's location (e.g., Google Maps link).
- **Open Time**: The opening time of the cafe (e.g., 8AM).
- **Close Time**: The closing time of the cafe (e.g., 9PM).
- **Coffee Rating**: A rating for the coffee quality (1 to 5 cups).
- **WiFi Rating**: A rating for the WiFi quality (1 to 5 bars).
- **Power Outlet Rating**: A rating for the availability of power outlets (1 to 5 plugs).

## Contribution

Contributions are welcome! If you find a bug or have a feature request, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

