# Roger Fang Portfolio Site

Live URL:
https://rogerfang28.github.io/

## What is in this repo

- index.html: page structure and content
- styles.css: visual design and responsive layout
- script.js: scroll reveal animation and footer year

## How to turn this into your real portfolio

1. Edit text content in index.html
2. Replace placeholder project names, descriptions, and links in the Projects section
3. Update contact info (email, LinkedIn) in the Contact section
4. Adjust skill chips in the Skills section
5. Optionally tweak colors and spacing in styles.css

## Publish with GitHub Pages (user site)

This repository name is rogerfang28.github.io, so it is a user site.

1. Commit and push changes:

	git add .
	git commit -m "Build initial portfolio site"
	git push origin main

2. In GitHub, open repository Settings -> Pages
3. Under Build and deployment, Source should be Deploy from a branch
4. Set branch to main and folder to /(root)
5. Save, then wait 1-2 minutes
6. Open https://rogerfang28.github.io/

## Fast local preview

Open index.html directly in a browser, or run a local server from this folder:

python -m http.server 5500

Then open:
http://localhost:5500

## Suggested next improvements

- Add a professional headshot and project screenshots in an assets folder
- Add a resume PDF and link it in the hero section
- Add analytics (for example, Plausible or Google Analytics)
- Add a simple contact form using Formspree or Netlify Forms
