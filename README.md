# SmartGate Website

A responsive, professional SmartGate landing page built with plain HTML, CSS and JavaScript.

## Project structure

```text
SmartGate-Website/
├── index.html
├── README.md
└── assets/
    ├── styles.css
    └── script.js
```

## Run locally

1. Download and extract the ZIP file.
2. Open the `SmartGate-Website` folder.
3. Double-click `index.html`, or open the folder in Visual Studio Code and use Live Server.

## Publish with GitHub Pages

1. Sign in to GitHub and create a new **public** repository, for example `smartgate-website`.
2. Extract this ZIP file on your computer.
3. Open the extracted folder and upload the contents of `SmartGate-Website` to the **root** of your GitHub repository.
   - `index.html` must be in the repository root.
   - Keep the `assets` folder and both files inside it together.
   - Do not upload only the ZIP file.
4. On GitHub, open your repository and select **Settings**.
5. Select **Pages** in the left sidebar.
6. Under **Build and deployment**, choose **Deploy from a branch**.
7. Select branch **main** and folder **/(root)**, then click **Save**.
8. Wait a few minutes. GitHub will display your website address in the Pages section. It will look like:
   `https://YOUR-USERNAME.github.io/smartgate-website/`

## Important notes

- This is a static front-end website and is compatible with GitHub Pages.
- The dashboard is an illustrative preview using sample data. It is not connected to a live gate, database, authentication service or hardware.
- The contact link opens the visitor's email application. Replace `hello@smartgate.example` in `index.html` with your real contact email before publishing.
- Google Fonts are loaded from the internet; the site uses fallback fonts if they are unavailable.
