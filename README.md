# Aklavya Verma — Portfolio

A single-page portfolio website built for software engineering, web development, and data analyst roles. Live, responsive, and self-contained — no build step, no dependencies, no backend.

**Live site:** `https://<your-github-username>.github.io/<repo-name>/` (fill this in once GitHub Pages is enabled — see below)

## About

This site introduces Aklavya Verma, an Information Science graduate (MVJ College of Engineering, Bengaluru) with experience across Java full-stack development, web technologies, and databases. It covers:

- **Home** — name, role, and a short intro
- **About** — profile summary and education
- **Skills** — languages, web development, databases, concepts, and soft skills
- **Work & Accomplishments** — internship experience, personal projects, certifications, and achievements
- **Contact** — a working contact form, plus direct email, phone, and LinkedIn links

## Features

- Fully responsive, single-file HTML/CSS/JS — works on desktop and mobile
- Sticky navigation with smooth scrolling between sections
- Résumé embedded directly in the page: viewable in a new tab or downloadable as a PDF, no external file needed
- Working contact form (via [FormSubmit](https://formsubmit.co)) that emails messages straight to the owner — no server required
- Muted, classy color palette (blues, browns, beige, greens, greys, maroons) with elegant serif typography

## Tech stack

Plain HTML, CSS, and vanilla JavaScript. No frameworks, no build tools, no `npm install`. Fonts are loaded from Google Fonts (Cormorant Garamond, EB Garamond, Tangerine); everything else is self-contained in `index.html`.

## Running locally

Just open `index.html` in any browser — no server needed for basic viewing. (Note: the contact form requires the page to be served over `http(s)`, so it won't send messages when opened directly as a local file; it works once deployed.)

## Deployment

This site is deployed for free with **GitHub Pages**:

1. Push/upload `index.html` to the root of this repository.
2. Go to **Settings → Pages**.
3. Under **Build and deployment → Source**, choose **Deploy from a branch**.
4. Set **Branch** to `main`, folder to `/ (root)`, and save.
5. Your live link appears at the top of that same page after a minute or two.

## Contact form setup

The contact form uses FormSubmit, which requires a one-time activation: the **first** message submitted through the live form triggers a confirmation email to the site owner's inbox. Click the confirmation link in that email once, and every submission after that is delivered automatically — no further setup needed.

## License

Personal portfolio — feel free to use this as a structural reference for your own site, but please don't reuse the content as-is.
