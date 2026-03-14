# WeaveForward Prototype

High-fidelity prototype for **WeaveForward**, created primarily by feeding wireframes to Claude.

The prototype simulates the system using a **JavaScript database embedded inside the HTML**, with generated records used to mimic real system behavior.

Images used in the prototype are **hosted externally** instead of being embedded directly in the HTML as Base64.

## Login

**Donor**
- Enter any email
- Enter any password

**TUAB**
- Email: kk@gmail.com
- Password: any value

## Implemented / Working

- Donation creation, editing, and cancellation
- TUAB claiming of donations
- TUAB confirmation of received donations
- Inventory ingestion from donations
- Donation Impact Dashboard
- Circular Economy Dashboard
- Map interface using Leaflet.js with OpenStreetMap and Nominatim
- Barangay / point-in-polygon searching works via GeoJSON hosted in a GitHub Gist

## Limitations

- No form validation rules
- 2FA prompt shown during login is not functional
- No admin interface
- Donation Impact Dashboard and Circular Economy Dashboard records are non existent, rather simulated
- "Subscribe for Premium Features" does not proceed beyond pressing the **Subscribe for ₱499** button
- Not connected to the ML API

This prototype is intended for **demonstration and interface simulation only**.
