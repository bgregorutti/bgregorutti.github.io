# Baptiste Gregorutti — Portfolio Site

A Jekyll-based portfolio site deployed on GitHub Pages using the [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) theme.

---

## Structure

```
.
├── _config.yml              # Site configuration
├── _data/
│   └── navigation.yml       # Top navigation menu
├── _pages/
│   ├── about.md
│   ├── projects.md          # Projects index
│   ├── safety-line.md       # Safety Line experience
│   ├── lumenai.md           # LumenAI experience
│   └── publications.md      # Publications & patent
├── _projects/               # Individual project pages (collection)
│   ├── delacroix.md
│   ├── cowspiracy.md
│   ├── annotix.md
│   └── sorbobot.md
├── assets/
│   └── css/
│       └── main.scss        # Custom CSS overrides
├── index.md                 # Home page
├── Gemfile
└── README.md
```

---

## Deployment — GitHub Pages

### 1. Create a GitHub repository

Name it: `baptiste-gregorutti.github.io` (or any name, then set baseurl in `_config.yml`)

### 2. Push the site

```bash
git init
git add .
git commit -m "Initial site"
git remote add origin https://github.com/YOUR_USERNAME/baptiste-gregorutti.github.io.git
git push -u origin main
```

### 3. Enable GitHub Pages

- Go to **Settings → Pages** in your repository
- Source: **Deploy from a branch**
- Branch: `main` / root

GitHub will build and deploy automatically. Your site will be live at:
`https://baptiste-gregorutti.github.io`

---

## Local Development

```bash
# Install dependencies
bundle install

# Serve locally
bundle exec jekyll serve

# Open in browser
open http://localhost:4000
```

Requires: Ruby, Bundler (`gem install bundler`)

---

## Updating content

- **Add a project**: create a new `.md` file in `_projects/` following the existing format
- **Update experience pages**: edit `_pages/safety-line.md` or `_pages/lumenai.md`
- **Update publications**: edit `_pages/publications.md`
- **Update navigation**: edit `_data/navigation.yml`

---

## Linking from LinkedIn

Once deployed, add the URL to your LinkedIn profile:
- Edit profile → **Contact info** → **Website** → add `https://baptiste-gregorutti.github.io`
- In each experience entry, you can add: *"Details: baptiste-gregorutti.github.io/projects"*
