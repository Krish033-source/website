# krbtech.xyz — Krishna Lal's Portfolio

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![No Framework](https://img.shields.io/badge/Framework-None%20needed-00ff6a?style=flat)

A single-page, hacker/terminal-themed developer portfolio for **Krishna Lal** — Machine Learning & MLOps Engineer. Built from scratch with plain HTML, CSS, and JavaScript — no frameworks, no build step.

🔗 **Live site:** [krbtech.xyz](https://krbtech.xyz)

---

## ✨ Features

- **Boot-sequence intro** — matrix code rain + terminal boot log + an animated circuit-mask that assembles, then breaks apart to reveal the site
- **Live hacker background** — multi-colored (green/red/blue) matrix rain plus randomly-spawning fake process logs (`compiling neural_net.py...`, `ssh krishna@10.0.0.4`, etc.) running behind every section
- **Typing-effect role line**, scroll-reveal animations, and animated skill bars
- Full sections: About, Education, Skills, Projects, Achievements, Community (GRID), Photo, Collab form, and Contact
- One-click **Resume download**
- **"Let's Build Something"** — a project-inquiry form that emails Krishna directly, no backend required
- Fully responsive across desktop and mobile

## 🛠️ Tech Stack

- **HTML5 & CSS3** — custom properties, keyframe animations, CSS Grid/Flexbox
- **Vanilla JavaScript** — Canvas API (matrix rain), IntersectionObserver (scroll reveals), Fetch API (form submission)
- **Google Fonts** — JetBrains Mono, VT323, IBM Plex Sans
- **FormSubmit.co** — serverless contact-form delivery

## 📁 File Structure

```
krbtech.xyz/
├── index.html        # the entire site — markup, styles, and scripts
├── Resume.pdf         # downloadable resume (linked from the Hero and Contact sections)
├── profile.jpg        # profile photo shown in the "Operator" section
└── grid-logo.png      # GRID community logo shown in the Community section
```

## 🚀 Running Locally

No dependencies, no build step — it's a single static HTML file.

```bash
git clone <repo-url>
cd krbtech.xyz
```

Then just open `index.html` in a browser, or serve it locally:

```bash
python3 -m http.server 8000
```

## 🌐 Deployment

Currently live at **krbtech.xyz**. To deploy your own copy:

1. Push this repo to GitHub.
2. Enable **GitHub Pages** (repo → Settings → Pages → deploy from `main`).
3. Add a `CNAME` file containing your domain, and point the domain's DNS to GitHub Pages.

(Netlify or Vercel also work great — just drag-and-drop the folder.)

## 🎨 Customizing

| What | File / Marker | How |
|---|---|---|
| Your photo | `profile.jpg` | Add a photo with this exact filename to the root folder |
| GRID logo | `grid-logo.png` | Add the logo with this exact filename to the root folder |
| GRID social links | `index.html` → search `gridLinkedin`, `gridInstagram`, `gridTwitter` | Replace each `href = "#"` with the real GRID profile URL |
| Contact form destination | `index.html` → search `FORM_ENDPOINT` | Swap the email in the FormSubmit URL for your own |
| Resume file | `Resume.pdf` | Replace with an updated resume, keeping the same filename |

## 📬 Contact

- **Email:** krilal324@gmail.com
- **GitHub:** [@Krish033-source](https://github.com/Krish033-source)
- **LinkedIn:** [krishna-lal-5b1a22321](https://linkedin.com/in/krishna-lal-5b1a22321)

---

Built with codes and caffeine ⚡ by **Krishna Lal**
