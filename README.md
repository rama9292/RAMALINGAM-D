# Ramalingam D – Mechanical Design Engineer Portfolio

A dark, cinematic personal portfolio for **Ramalingam D**, an aspiring Mechanical Design Engineer (B.E. Mechanical Engineering, Chettinad College of Engineering & Technology, Karur, batch 2027).

The site is a single self-contained HTML file. It has no build step and no dependencies to install.

## Sections

- **Intro:** animated loading sequence with a percentage counter
- **Hero:** animated CAD-style grid, particles and light trails, with letter-by-letter name reveal
- **About:** short profile with an animated portrait
- **Skills:** tabbed groups (CAD, Analysis, Engineering, Other)
- **CAD projects:** ten SolidWorks-style renders with a detail view for each
- **Experience:** internships, academic projects, certifications and achievements
- **AXISFORGE CAD:** animated brand section
- **Resume:** preview and PDF download
- **Contact:** LinkedIn, email and a message form

## Run locally

1. Download `index.html`.
2. Open it in any modern browser.

An internet connection is needed only for the Google Fonts (Sora and Space Grotesk).

## Deploy with GitHub Pages

1. Create a new repository on GitHub and upload `index.html` and this `README.md`.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. After a minute, the site is live at `https://<your-username>.github.io/<repository-name>/`.

The page also works on Netlify, Vercel and Cloudflare Pages by uploading the file.

## Customise

Everything is inside `index.html`.

| What | Where |
| --- | --- |
| Email and LinkedIn | `CFG` object at the top of the `<script>` |
| Projects | `PR` array in the script (title, image key, description, objective) |
| Skills | `SK` object in the script |
| Colours | CSS variables in `:root` (`--bg`, `--navy`, `--silver`, `--blue`) |
| Resume PDF | `PDF_B64` constant (base64 of the PDF) |
| Images | `IMG` object (base64 JPEGs) |

To use separate image or PDF files instead of embedded data, replace the base64 strings with file paths such as `images/steam-engine.jpg`.

## Features

- Canvas animations: moving grid, particles, light trails and an AxisForge ring emblem
- Magnetic buttons, custom cursor and card tilt on desktop
- Horizontal project rail with scroll snapping and a detail dialog
- Responsive layout for phones, tablets and desktops
- Respects `prefers-reduced-motion`
- Lighter hero visuals on small screens

## Notes

- The resume download uses a Blob, so it works when the file is opened locally or hosted.
- The contact form opens the visitor's email app with the message filled in. It does not send mail from a server.
- Project pages show "Software used: To be added" until you fill it in.
- The resume PDF may contain personal details. Check it before publishing.

## Contact

- LinkedIn: https://www.linkedin.com/in/ramalingam-d-77ab22390
- Email: ramalingam9292@gmail.com
- Location: Tirupur, Tamil Nadu, India

## Credits

**RAMALINGAM** · Aspiring Mechanical Design Engineer · **AXISFORGE CAD**
