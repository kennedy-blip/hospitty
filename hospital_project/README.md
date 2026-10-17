# Hospital Management & Patient Portal (`St. Jude Medical Center`)

A clean, responsive front-end web appl ication template designed for hospitals, clinics, and medical centers. It enables patients to explore clinical departments, view specialist profiles, access emergency contact num bers, and submit appointment requests.

## Project Structure

```text
hospital_project/
├── index.html      # Ma in resp onsive  web page (HTML5, embedded CSS3, and interactive JS)
└── README.md       # Project docum entation an d set up ins truc t ions
```

## Features

- **24/7 Emergency Banner:** Prominent top bar displaying emergency hotline and ambulance dispatch details.
- **Responsive Navigation:** Sticky header with smooth anchor navigation across sections.
- **Clinical Departments Grid:** Overview of core medical specialties (Cardiology, Neurology, Pediatrics, Orthopedics, Oncology, Emergency & Trauma).
- **Specialist Directory:** Highlighted physician cards detailing credentials and clinical focus.
- **Interactive Appointment Booking:** Client-side validated booking form with instant confirmation feedback.
- **Hospital Information Footer:** Visiting hours, physical address, and general support contacts.

## Getting Started

1. **Extract the Archive:** Unzip `hospital-project.zip` to your desired directory.
2. **Open in Browser:** Double-click `index.html` or open it via any modern web browser (Chrome, Firefox, Safari, Edge).
3. **Local Development Server (Optional):**
   ```bash
   # Using Python 3
   python -m http.server 8000
   ```
   Then navigate to `http://localhost:8000` in your browser.

## Customization

- **Branding & Colors:** Modify the CSS custom properties under `:root` in `index.html` (`--primary`, `--secondary`, `--accent`) to match your healthcare organization's color palette.
- **Backend Integration:** Connect the `#bookingForm` submit handler in the `<script>` tag to a REST API endpoint (e.g., Node.js/Express, Django, or FastAPI) to persist patient appointment requests into a database.

## License

This project is open-source and available under the [MIT License](https://opensource.org/licenses/MIT).
