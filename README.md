# Route Optimization System

Web application developed with Flask and Google Maps API to calculate and display the shortest driving route between locations in Mexico.

## Features

- Route calculation between locations
- Interactive map visualization
- Real driving routes using Google Maps Directions API
- Distance calculation in kilometers
- Responsive user interface

## Technologies

- Python
- Flask
- HTML
- CSS
- JavaScript
- Google Maps API

## Project Structure

```text
project/
│
├── app.py
├── requirements.txt
├── README.md
│
├── static/
│   └── styles.css
│
└── templates/
    └── index.html
```

## Installation

Clone the repository:

```bash
git clone https://github.com/CristelMartinez/RutaMasCorta.git
```

Enter the project directory:

```bash
cd RutaMasCorta
```

Create a virtual environment:

```bash
python -m venv venv
```

Activate the virtual environment:

### Windows

```bash
venv\Scripts\activate
```

### macOS / Linux

```bash
source venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## Running the Project

Run the Flask server:

```bash
python app.py
```

Open in browser:

```text
http://127.0.0.1:5000
```

## Google Maps API Configuration

Replace the API key in `templates/index.html`:

```html
YOUR_GOOGLE_MAPS_API_KEY
```

with your own Google Maps API key.

Required APIs:
- Maps JavaScript API
- Directions API

## How It Works

The backend developed with Flask provides route coordinates between two locations.

Google Maps Directions API calculates and renders the real driving route on the map interface.

## Future Improvements

- Real-time traffic analysis
- Route history
- Multiple route comparison
- Travel time estimation
- Dynamic city database

## Author

Cristel Martinez
