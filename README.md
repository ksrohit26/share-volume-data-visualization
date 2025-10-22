# Share Volume Data Visualization

This project fetches and processes share volume data for a given company using SEC's API and displays the maximum and minimum share counts in an interactive HTML page.

## How to run

1. Ensure you have a static server environment to serve the files (e.g., using Python's simple HTTP server).
2. Open `index.html` in a browser.
3. The page initially loads data for the default CIK. You can change the URL parameter `?CIK=XXXXXXXXXX` to fetch data for another CIK.
4. The page dynamically updates the entity name, and max/min share counts based on fetched data.

## Files
- `index.html`: Main HTML page displaying the data.
- `static/uid.txt`: Contains the attached UID data.
