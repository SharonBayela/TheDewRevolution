# The Dew Revolution — Website

Static HTML5 template for **The Dew Revolution** — dairy juice manufacturing, poultry & livestock farming, and transportation. *"Where Success Meets Greatness."*

No build step, no framework — plain HTML, CSS and a touch of vanilla JS, ready to serve as-is or host on GitHub Pages.

## Structure

```
├── index.html          Home
├── about.html           About — founder & CEO, mission / vision / objectives
├── production.html      Dairy juice, poultry & livestock, transportation
├── people.html          Team
├── events.html          Events
├── careers.html         Careers / open roles
├── contact.html         Contact details + form + social links
├── css/style.css        All styling (single stylesheet, CSS variables)
├── js/main.js           Mobile nav toggle + footer year
└── assets/img/          Logo and photos
```

## Before you publish — things to fill in

Every placeholder is written in **[Edit: ...]** or **[Add ...]** style so it's easy to find with a search across the project. Key spots:

- **about.html** — founder/CEO name + bio, mission, vision, objectives, values
- **production.html** — dairy juice details, livestock/poultry numbers, fleet details
- **people.html** — team member names, roles, photos (swap `assets/img/team-member.jpg` and duplicate `.team-card` blocks)
- **events.html** — real event dates, titles, locations
- **careers.html** — real job openings
- **contact.html** — phone, email, address, hours, map embed
- **Every page footer** — phone number and email in the footer columns
- **Social links** — every `<a href="#">` next to the LinkedIn / Instagram / X icons across the header-adjacent contact button, footer, and contact page. Search for `social-btn` to find them all, and update the `mailto:info@thedewrevolution.com` and `mailto:careers@thedewrevolution.com` addresses to your real inboxes.

## Notes on the design

- **Colors** come straight from your logo: deep navy, sky blue, warm amber (from the Juicy Dew label), and a soft cream background.
- **Badge-shaped photo frames** echo the shield shape in the logo.
- **Wave dividers** and small "dew drop" dots in the hero/banners are a nod to the brand name.
- Livestock icons (cattle, pigs, goats, layer hens, broilers) on the Production page are simple custom line-art placeholders, since photos weren't supplied for those — swap in real photos any time by replacing the `.icon-badge` block with an `<img>`.
- The contact form is styled but **not wired to send email yet** — connect it to a service like Formspree, EmailJS, or your own backend before going live.

## Running locally

Just open `index.html` in a browser, or serve the folder with any static server, e.g.:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploying

This is ready for **GitHub Pages**: push to a repo, enable Pages on the `main` branch (root), and the site will be live.
