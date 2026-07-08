# Kevin Tu's GitHub Pages

This repository powers a small resume-style personal site on GitHub Pages. The homepage presents a clean portfolio landing page, and the assignment subpage keeps coursework or practice work organized in the same visual style.

## What is included

- A polished resume homepage at the repository root
- An assignment subpage for ECV-related work
- A responsive layout that works on desktop and mobile
- Simple static HTML and CSS with no build step required

## Project Structure

```text
.
├── index.html
├── README.md
└── assignment/
	└── index.html
```

## Local Preview

You can open `index.html` directly in a browser, or run a local static server if you prefer:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000/`.

## GitHub Pages

If GitHub Pages is enabled for this repository, the root `index.html` becomes the public homepage. The assignment page is available at `assignment/`.

## Editing the Site

- Update the homepage content in `index.html`
- Add more assignment or project pages under `assignment/`
- Replace the placeholder contact and profile details with your own information

## Next Ideas

- Add education and experience sections
- Add links to GitHub, LinkedIn, or email
- Expand the projects section with screenshots and write-ups