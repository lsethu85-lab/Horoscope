# VedicSuite — Tamil Calendar, Panchangam & Horoscope Web App

VedicSuite is a single-page web application for Tamil / Vedic astrology utilities, horoscope profile management, Tamil calendar viewing, daily Panchangam, Rahu Kalam, Emakandam, Muhurtham details, and AI-assisted compatibility / property / business recommendations.

## Author

**Sethuraman Lakshminarayanan**

---

## Features

### Horoscope Profiles

- Add, edit, duplicate, export, print, and delete horoscope profiles.
- Calculates and displays:
  - Rasi / Moon Sign
  - Nakshatra and Pada
  - Lagna / Ascendant
  - Navamsa
  - Sun Sign
  - Tithi
  - Dasa / Bhukti
  - Planetary positions
  - Gochar / transit view
  - Yogas and Doshas

### Tamil Calendar

- Year-based Tamil calendar view.
- Select Gregorian year.
- Filter by Tamil month.
- Displays:
  - English date
  - Tamil month and Tamil date
  - Weekday in English and Tamil
  - Tithi
  - Nakshatra
  - Moon Rasi
  - Rahu Kalam
  - Emakandam / Yamagandam
- Highlights special days:
  - Amavasai
  - Pournami
  - Ekadashi
  - Ashtami
  - Chaturdashi

### Daily Panchangam

- Daily Panchangam view with:
  - Tamil date
  - Tithi
  - Nakshatra
  - Moon Rasi
  - Sun Sign
  - Yoga
  - Karana
  - Rahu Kalam
  - Emakandam
  - Gulika
- Includes upcoming special tithi days.

### Rahu Kalam & Emakandam

- Dedicated tab for daily Rahu Kalam and Emakandam.
- Shows:
  - Today's Rahu Kalam
  - Today's Emakandam / Yamagandam
  - Today's Gulika
  - Next 45 days avoidance windows

### Muhurtham Details

- Muhurtham listing for:
  - Marriage
  - Property registration
  - Business launch
- Includes:
  - Muhurtham score
  - Recommended use
  - Practical checklist
  - `.ics` calendar export

### Wedding Compatibility

- AI-assisted compatibility score.
- Detailed breakdown includes:
  - Dina / Tara balance
  - Gana and temperament
  - Rasi and Rasi Athipathi
  - Rajju / Nadi review
  - Kuja Dosha / Dasa Sandhi review

### Property Recommendation

- AI-assisted property suitability score.
- Detailed breakdown includes:
  - Lagna and 4th house support
  - Mars / Saturn land factors
  - Finance and loan timing
  - Document / registration window
  - Muhurtham fit

### Business Recommendation

- AI-assisted business launch score.
- Detailed breakdown includes:
  - 10th house strength
  - Mercury / Jupiter business logic
  - Venus / Mars market energy
  - Cash-flow risk
  - Launch Muhurtham fit

### Reports

- Browser print support.
- Save as PDF using browser print tools.
- JSON export for horoscope profiles.

---

## Tech Stack

This project is built as a static single-page application.

- HTML
- CSS
- Vanilla JavaScript
- LocalStorage for persistent data
- Browser-based astronomical / astrology calculations
- No backend required

---

## Project Structure

```text
.
├── index.html
└── README.md
```

---

## How to Run

### Option 1: Open Directly

Simply open `index.html` in a browser.

```text
Double-click index.html
```

### Option 2: Run with a Local Server

Using Python:

```bash
python -m http.server 8080
```

Then open:

```text
http://localhost:8080
```

---

## Deployment

This app can be deployed on any static hosting platform.

Recommended options:

- GitHub Pages
- Netlify
- Vercel
- Azure Static Web Apps
- Any basic web hosting server

### GitHub Pages Deployment

1. Create a GitHub repository.
2. Upload `index.html` and `README.md`.
3. Go to repository **Settings**.
4. Open **Pages**.
5. Select the branch, usually `main`.
6. Save and publish.

---

## LocalStorage Notes

The app stores user-created profiles and form data in the browser's LocalStorage.

Stored data may include:

- Horoscope profiles
- Selected language
- Theme preference
- Saved forms
- Compatibility / recommendation results

If old or incorrect data appears after an update, clear browser site storage and reload the page.

---

## Accuracy Notes

This application is designed for personal astrology, calendar, and planning assistance.

Important notes:

- Tamil calendar and Panchangam values are calculated in-browser.
- Rahu Kalam and Emakandam use standard daytime divisions.
- Exact values may vary based on:
  - Location
  - Sunrise / sunset time
  - Panchangam tradition
  - Ayanamsa selection
  - Mean vs true node usage
- For religious ceremonies, marriage decisions, property registration, or business launch timing, verify final details with a qualified astrologer or local Panchangam.

---

## Known Limitations

- Static browser-only calculation engine.
- No backend ephemeris service.
- No Swiss Ephemeris server integration.
- Sunrise and sunset are approximate unless manually enhanced.
- Tamil month start dates are approximated for browser-side use.
- Panchangam values should be treated as guidance, not final ritual authority.

---

## Suggested Future Enhancements

- Add accurate city-based sunrise and sunset calculation.
- Add full Panchangam API integration.
- Add Swiss Ephemeris backend support.
- Add PDF horoscope report generation.
- Add Tamil language translations for all labels.
- Add configurable ayanamsa selection.
- Add true node / mean node toggle.
- Add event reminders and calendar sync.

---

## Screenshots

Add screenshots here:

```markdown
screenshots/dashboard.png
screenshots/tamil-calendar.png
screenshots/panchangam.png
```

---

## License

This project is released for personal and educational use.

You may add a license such as:

```text
MIT License
```

or customize based on your intended usage.

---

## Author

Created by **Sethuraman Lakshminarayanan**.

---

## Disclaimer

This software provides astrology and calendar calculations for informational and planning purposes only. It should not be used as the sole basis for financial, legal, medical, marriage, property, or business decisions. Always consult qualified professionals where appropriate.
