# Travel Route App

This is a Flask-based web application that allows users to find routes from a start location to a destination with a specified service (e.g., a restaurant) along the way. The app leverages Google Maps API for location and route information.

## Features

- Input start and destination locations.
- Specify a service to look for along the route.
- Display routes with the specified service and deviation details.
- Interactive map to show the route with waypoints.

## Prerequisites

- Python 3.7 or higher
- Flask
- Requests
- Google Maps API Key

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/deepusnath/travel-route.git
    cd travel-route
    ```

2. **Create a virtual environment and activate it:**

    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

3. **Install the required packages:**

    ```bash
    pip install flask requests
    ```

4. **Replace `YOUR_GOOGLE_API_KEY` with your actual Google API key in `app.py`:**

    ```python
    GOOGLE_API_KEY = 'YOUR_GOOGLE_API_KEY'
    ```

## Usage

1. **Run the Flask application:**

    ```bash
    python3 app.py
    ```

2. **Open your web browser and go to:**

    ```
    http://127.0.0.1:5001
    ```

3. **Input the start location, destination location, and the service you are looking for. Click "Find Route" to see the routes and details.**


## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any changes.

## Acknowledgements

- Google Maps API
- Flask Framework

## Contact

For any questions or feedback, please contact deepusnath@gmail.com.
