# Leaflet Demo

This project visualizes the paths of hurricanes from 2020 using Leaflet.js and data from a CSV file. The map displays hurricane tracks with color-coded lines based on their category.

## Features

- Interactive Leaflet map displaying hurricane paths.
- Markers for storm positions with popup details.
- Color-coded hurricane categories with a legend.
- Uses OpenStreetMap tiles for the base map.

## Requirements

- HTML, CSS, JavaScript
- Leaflet.js
- PapaParse
- OpenStreetMap

## Installation and Usage

### 1. Clone the repository:

```bash
git clone https://github.com/okjazim/Leaflet-Demo
cd Leaflet-Demo
```
### 2. Start a localhost server:

#### Using Python (built-in in most systems):

For Python 3:
```bash
python -m http.server 8000
```
#### Using serve (if installed via npm):
```bash
npx serve .
```
#### Using PHP (if installed):
```bash
php -S localhost:8000
```
#### Using BusyBox (common on Linux):
```bash
busybox httpd -f -p 8000
```
### 3. Usage
#### Then, open your browser and go to:
```bash
http://localhost:8000/
```

## File Structure
```bash
Leaflet-Demo/
│── index.html          # Main file containing the map and logic
│── hurricanes2020.csv  # Data file contains coordinates
│── favicon-16x16.png   # Icon file favicon Icon
```

## Legend Colours

The storm paths are colored based on their category:

- Tropical Storm - Blue
- Tropical Depression - Gray
- Subtropical Storm - Cyan
- Category 1 Hurricane - Green
- Category 2 Hurricane - Yellow
- Category 3 Hurricane - Orange
- Category 4 Hurricane - Red
- Category 5 Hurricane - Purple
  
## Screenshots
![Screenshot (15)](https://github.com/user-attachments/assets/93490d50-9137-48dd-bfb7-c01e661fca7a)
![Screenshot (16)](https://github.com/user-attachments/assets/eec324ca-a0fe-4a6d-be4c-b3450b5016dc)
![Screenshot (17)](https://github.com/user-attachments/assets/2af92b0e-4507-42e1-8454-44f2907a7aaa)
## License

This project is open-source and available under the MIT License.
