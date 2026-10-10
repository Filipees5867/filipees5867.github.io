# Behrooz Taheri — Personal Website

A fast, static personal academic website (HTML + CSS + JavaScript, no build step), ready for **GitHub Pages**.

## Folder structure

```
index.html          Home
publications.html   Publications (search + filters + copy citation)
experience.html     Work experience & education
projects.html       Projects
honors.html         Honors, reviewing, certifications
contact.html        Contact & references
404.html            "Page not found" page

data/               <-- ALL CONTENT LIVES HERE (edit these files)
  site.js           Name, bio, links, menu, research interests, skills
  publications.js   Papers
  experience.js     Education, work experience, projects
  honors.js         Honors, reviewer list, certificates, references

assets/img/         Photos (profile.jpg, avatar.jpg, favicon.png)
assets/cv/          Your CV PDF (Download CV button)
assets/css/         Styles (colors at the top of style.css)
assets/js/main.js   Site engine (normally no need to edit)
```

## Adding content

- **New paper:** open `data/publications.js`, copy one `{ ... },` block, paste it, edit. It is sorted and counted automatically.
- **New job / degree / project:** `data/experience.js`
- **New award / reviewer journal / certificate:** `data/honors.js`
- **Google Scholar, LinkedIn, ORCID...:** `data/site.js` → `links`
- **New CV:** replace `assets/cv/Behrooz-Taheri-CV.pdf` (keep the same name)
- **New photo:** replace `assets/img/profile.jpg` (portrait, ratio 4:5, e.g. 720×900)

## Preview locally

Just double-click `index.html`. Everything works offline (fonts need internet).

## Publish on GitHub Pages

1. Create a repository named **`<your-username>.github.io`**.
2. Upload all files from this folder (not the folder itself) to the repository root.
3. Settings → Pages → Source: *Deploy from a branch* → `main` / `(root)` → Save.
4. After 1–2 minutes the site is live at `https://<your-username>.github.io/`.
