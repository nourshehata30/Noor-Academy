# Noor Academy

A seven-page website for Quran and Arabic education, built with HTML, CSS and vanilla JavaScript.

## Pages

- Home: academy introduction and course navigation.
- About: the academy's approach to teaching.
- Courses: an overview of the available courses.
- Qaida, Recitation and Memorisation: individual course details.
- Contact: an enquiry form with client-side validation.

## Run locally

Download or clone the repository, keep the HTML and image files together, and open `index.html` in a browser. No package installation or build step is required.

If Python is installed, you can alternatively serve the folder locally:

```sh
python -m http.server 8000 --bind 127.0.0.1
```

Then open `http://127.0.0.1:8000`.

## Implementation notes

- Styles and scripts are embedded in the HTML pages.
- The contact form uses FormSubmit and Google's DNS-over-HTTPS service. Submitting it sends data to external services; avoid submitting personal data when exploring the project.
- Login and registration markup is a front-end prototype, not a working authentication system. Do not enter real passwords.
- The existing home-page script references an undeclared `closeButtons` variable; the JavaScript needs further work before production use.
- Contact-form email checks do not establish whether an individual mailbox exists.

This repository preserves the original website code and its accompanying image assets. Local Python environments and development files are not included.
