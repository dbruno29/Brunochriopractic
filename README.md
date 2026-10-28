# Bruno Chiropractic Center — website

Static site for brunochiropractic.com (North Providence, RI). No build step: edit the HTML, CSS and JS directly and push to `main`; GitHub Pages serves it.

- `index.html`, `about.html`, `services.html`, `new-patients.html`, `patient-education.html`, `contact.html`, `legal.html`
- `css/styles.css` — colors and fonts are tokens at the top of the file
- `js/main.js` — menu, "open now" badge, appointment form
- `img/` — logo (SVG + PNG), practice photos, stock photos
- `forms/new-patient-forms.pdf` — placeholder, replace with the office's intake forms

Appointment requests send to the office inbox via FormSubmit; the first submission from a new domain triggers a one-time activation email the office must click.
