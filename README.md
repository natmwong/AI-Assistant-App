# TravelPlannerApp

A single-file web app (travelplannerapp.html) for planning trips, adding destinations, and exporting/importing simple trip data.

## File
- travelplannerapp.html — main application file. Place in the same folder as this README.

## Purpose
Lightweight client-side travel planner to create trips, manage destinations, estimate dates, and export/import trip data as JSON.

## Features
- Create and name trips
- Add/edit/remove destinations
- Rearrange destinations
- Set travel dates and notes
- Export trip data to JSON
- Import trip JSON to restore a trip
- Works entirely in the browser (no server required)

## Requirements
- Modern web browser (Chrome, Edge, Firefox, Safari)
- Optional: static file server for CORS/Live Reload (recommended for development)

## Quick start
1. Copy `travelplannerapp.html` to a local folder (for example the project folder).
2. Open the file in your browser:
    - Double-click the file, or
    - Right-click → Open with → your browser
3. (Optional) Run a local server for consistent behavior:
    - Python 3: `python -m http.server 8000`
    - Then open `http://localhost:8000/travelplannerapp.html`

## Usage
- Create a new trip and give it a name.
- Click "Add destination" to add locations and optional notes/dates.
- Reorder or delete destinations as needed.
- Use "Export" to download a JSON file of the trip.
- Use "Import" to upload a previously exported JSON to restore the trip.

## Development notes
- Single HTML file — markup, styles, and scripts live in the same file.
- To edit: open in a code editor (VS Code, Sublime, etc.).
- For small changes, refresh the browser to see updates.
- Consider using browser DevTools for debugging.

## Contributing
- Open issues or send pull requests with focused changes.
- Keep changes minimal and include a short description.

## License
MIT — adapt as needed. Include full license file in the project root if required.

## Contact
Add project-specific contact or repository link here.
