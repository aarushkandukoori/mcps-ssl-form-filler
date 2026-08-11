# MCPS SSL Hours Form Filler

**Live site: https://aarushkandukoori.github.io/mcps-ssl-form-filler/**

A free, unofficial web tool that fills out **MCPS Form 560-51 — Student Service Learning Activity Verification** for Montgomery County Public Schools students.

- ✏️ Fill out the form with a clean, mobile-friendly interface (school dropdown, phone/date formatting, EIN boxes handled for you)
- 📄 Generates the **official PDF**, completed, right in your browser
- ✉️ Opens a ready-to-send **email draft to your counselor / SSL coordinator** (Gmail, your mail app, or direct share with the PDF attached on supported devices)
- 💾 Your answers auto-save on your device so you can come back later
- 🔒 **100% private** — nothing is ever uploaded to a server; the PDF is filled entirely in your browser with [pdf-lib](https://pdf-lib.js.org/)

## How it works

1. Fill in Section I (student info), Section II (organization info, if you have it), and Section III (your reflection).
2. Enter your counselor's email and hit **Generate My Completed Form** — the filled PDF downloads.
3. Tap the Gmail / Mail button to open a pre-written email, **attach the downloaded PDF**, and send. On phones, the Share button attaches the PDF automatically.

Your supervisor still needs to sign Section II by hand (or with a PDF signing tool) for the form to be official.

## Disclaimer

This tool is made by a student and is **not affiliated with, endorsed by, or connected to Montgomery County Public Schools**. The official form and instructions are at [montgomeryschoolsmd.org](https://ww2.montgomeryschoolsmd.org/departments/forms/pdf/560-51.pdf). Always follow your school SSL coordinator's submission instructions and deadlines.

## Development

It's a single static page (`index.html`) plus the blank official PDF (`560-51.pdf`). No build step — open `index.html` via any local web server:

```bash
python3 -m http.server
```

## License

MIT (for the code — the form itself belongs to MCPS).
