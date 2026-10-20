# AWS Portfolio Tracker **[Live Demo](https://main.dge1x5t4njog6.amplifyapp.com)**

A simple static portfolio website by **Hooman Vahdat**, hosted on AWS Amplify and deployed automatically from this repository.

## About

This site is built with plain HTML and needs no build step. It is a lightweight home for my work as a software developer and data science student.

## Tech

- HTML (add CSS and JavaScript as the site grows)
- Hosting: [AWS Amplify Hosting](https://aws.amazon.com/amplify/)
- Source control and deploys: GitHub, branch `main`

## Project structure

```
.
├── index.html     # Main page
└── README.md      # This file
```

If you add styles and images later, keep them in their own folders and link them with relative paths:

```
├── css/
│   └── style.css
└── images/
    └── photo.jpg
```

## Run locally

No setup is needed. Clone the repo and open `index.html` in a browser:

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPO.git
cd YOUR-REPO
```

Then double-click `index.html`, or serve the folder with a local server:

```bash
python -m http.server 8000
```

and visit http://localhost:8000.

## Deployment

The site deploys automatically through AWS Amplify:

1. Edit a file and commit to the `main` branch.
2. Push to GitHub.
3. Amplify detects the commit, rebuilds, and publishes the update within a minute or two.

Amplify settings used:

| Setting | Value |
| --- | --- |
| Framework | None |
| Build command | *(empty)* |
| Build output directory | `/` |
| Production branch | `main` |

## Notes

- File and folder names are case-sensitive on the server, so use lowercase names and avoid spaces.
- `index.html` must stay at the root of the repository.

## Contact

Hooman Vahdat
**My GitHub Portfolio:** https://github.com/hoomanv3xo
**My Portfolio Site:** https://hooman-codes.ca


