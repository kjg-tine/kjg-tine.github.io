# Kristine Joy Torres — Portfolio

A responsive, accessible portfolio built with semantic HTML, CSS and lightweight vanilla JavaScript.

## Run locally

Open a terminal in this folder and run:

```sh
python -m http.server 8000
```

Visit http://localhost:8000 in your browser.

No npm install or bundler is required. Internet access loads the Lexend Google Font and Phosphor Icons web package; system-font and text fallbacks remain usable offline.

## Before publishing

- GitHub profile and both Java project repository links are already configured. Replace **contact placeholders** in `index.html` for TNT, GOMO, email, LinkedIn, Facebook, Instagram, and Discord. For each contact, replace both `href` and the displayed text (where relevant), then remove its `data-placeholder-contact="true"` attribute to activate the link. Discord uses your numeric Discord user ID in its URL (not your display name).
- Optionally add your portrait and verified screenshots/links for projects.
- Replace relative `og:image` with the deployed absolute URL, and add a canonical URL once you have a domain.
- Do not describe TESDA certification as awarded until officially received. Current wording is "Training completed · Certification pending".
- Publish on GitHub Pages, Netlify, or Vercel. Verify layout with browser responsive tools and test keyboard navigation.

## Project gallery
Both Java console projects are now featured with locally stored screenshots and links to their GitHub repositories. Open Projects, then select View screenshots to browse. Login screenshots showing credentials were intentionally omitted from the published gallery. The uploaded SQL database dump is also intentionally excluded because it contains account records and hashed passwords.


## CineBook team capstone
Includes 8 selected screenshots in `images/cinebook-01.png` through `cinebook-08.png`. Screenshots with login credentials, account settings, or payment reference numbers were excluded to avoid publishing sensitive information. The SQL database dump is intentionally NOT included. The project links to the team repository at https://github.com/audreyyabes/b326-cinebook-group3 .


### Updated navigation
Home contains the hero, tools marquee and six overview cards. Projects jumps to Selected Work (Load Registration App, Music Recording Management System, CineBook). About jumps to Student Mindset / Builder Energy. The three sample projects were removed.

Contact: Provided TNT, GOMO, email, Facebook and Instagram links were filled in. LinkedIn remains a placeholder; Discord is listed as a username until a numeric profile ID is provided.


### Training, participation, and AI skills

- The AppBuildersPH Hackathon 2026 Certificate of Participation is included under `certificates/` with a thumbnail and viewable PDF. It documents Kristine Torres's participation in Team Override on October 9–10, 2026.
- TESDA Java Programming NC III is identified as training completed, certification pending.
- AI-Assisted Development is listed as a skill; the About section explains responsible use for brainstorming, coding, debugging, and learning.
- Sidebar photo and social icons from the prior requests are included.


## Coquette edition additions
- Animated pastel bow/floral background and a user-selectable light/dark theme (saved in browser).
- PUP Lost & Found Figma prototype linked directly; conceptual art is not a verified Figma screenshot.
- STRIX Android prototype linked to user-provided Drive URL. Offline AI inference is **not** claimed as verified.
- To enable resume download, put your PDF at `resume/Kristine-Joy-Torres-Resume.pdf` and remove `data-resume-pending="true"` from the resume link in index.html.
- No hosting push made. Deploy by committing these extracted files at repo root.
