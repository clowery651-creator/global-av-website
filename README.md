# Global A.V. — Company Website

Marketing site for Global A.V., a Florida-based low-voltage/AV integration company (Tampa Bay, Orlando, Jacksonville, Sarasota/Bradenton). Single-file HTML/CSS/JS, no build step or dependencies.

## Features

- **Local service-area finder**: enter a ZIP code or city (or share your location) to check whether you're in Global A.V.'s coverage area, matched against the company's actual Tampa Bay / Orlando / Jacksonville / Sarasota-Bradenton territory.
- **Quote request form**: opens the visitor's email client with a pre-filled message to `info@globalavfl.com` — no backend required.
- Services, service-area, credentials, and process sections built from the company's business documentation.

## Running locally

Open `index.html` directly in a browser.

## Notes

- The "Use My Location" button reverse-geocodes via the free OpenStreetMap Nominatim API (no key required) to get a city/ZIP, then runs it through the same local matching logic as manual entry.
- Company contact info, service area, and licensing details (FL Class ES Low-Voltage Contractor) are sourced from the company's internal business documentation.
