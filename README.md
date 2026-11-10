# IRP LMS

A responsive, multi-page learning management website for discovering video tutorials and contacting the IRP LMS support team. Built as a static HTML and CSS assignment with no JavaScript, framework, or backend.

## Technologies

- HTML5
- CSS3

## Features

- Shared, responsive navigation across the home, courses, and contact pages
- Learning journey overview and course discovery sections
- Nine embedded YouTube tutorials
- Responsive layouts for desktop, tablet, and mobile screens
- Accessible semantic markup, image alt text, keyboard focus styles, and labeled form fields
- Contact links for email and telephone
- Client-side required-field and email-format validation from native HTML form controls

## Project Structure

```text
IRP-LMS/
├── index.html
├── courses.html
├── contact.html
├── style.css
└── README.md
```

## Run Locally

No build tools or dependencies are needed. Open `index.html` in a modern web browser. The other pages are linked from the shared navigation. An internet connection is needed to load the Cloudinary images and YouTube embeds.

## Publish with GitHub Pages

1. Create a new **public** repository on GitHub.
2. Add the contents of this `IRP-LMS` folder to the repository root, then commit and push them to the default branch. For example, from a terminal in this folder:

   ```bash
   git init
   git add index.html courses.html contact.html style.css README.md
   git commit -m "Add IRP LMS static website"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
   git push -u origin main
   ```

3. On GitHub, open the repository's **Settings**, choose **Pages**, and under **Build and deployment** select **Deploy from a branch**.
4. Choose the `main` branch and `/ (root)` folder, then select **Save**.
5. Wait for the Pages deployment to finish. GitHub will show the published website URL in the Pages settings. The home page is `index.html`; `courses.html` and `contact.html` are available at their matching paths.

The contact form is presentation-only: it uses native browser validation but does not send or store submissions. The Sign In control is also visual only, as this project has no authentication or backend.
