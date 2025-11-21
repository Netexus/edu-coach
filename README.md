# EduCoach Landing Page

A simple, modern landing page for the EduCoach educational project.

## Project Structure

- `index.html`: The main HTML file containing the content.
- `styles.css`: The styling for the website.
- `script.js`: Simple animations and interactions.

## How to Deploy to GitHub Pages

You can host this website for free using GitHub Pages. Here is the easiest way to do it:

### Option 1: Uploading Files (Easiest)

1.  **Create a GitHub Account**: If you don't have one, go to [github.com](https://github.com) and sign up.
2.  **Create a New Repository**:
    *   Click the "+" icon in the top right corner and select "New repository".
    *   Name it something like `edu-coach-site`.
    *   Make sure it is **Public**.
    *   Click "Create repository".
3.  **Upload Files**:
    *   On the next screen, look for the link that says "uploading an existing file".
    *   Drag and drop `index.html`, `styles.css`, and `script.js` into the upload box.
    *   Commit the changes (click the green "Commit changes" button).
4.  **Activate GitHub Pages**:
    *   Go to the repository **Settings** tab.
    *   On the left sidebar, click on **Pages**.
    *   Under **Build and deployment** > **Branch**, select `main` (or `master`) from the dropdown menu.
    *   Click **Save**.
5.  **Visit Your Site**:
    *   Wait a minute or two. Refresh the page.
    *   You will see a link at the top saying "Your site is live at...". Click it to see your website!

### Option 2: Using Git (For Developers)

1.  Initialize a git repository:
    ```bash
    git init
    git add .
    git commit -m "Initial commit"
    ```
2.  Push to GitHub and follow the same steps in "Activate GitHub Pages" above.

## Customizing

- **Text**: Edit `index.html` to change the text content.
- **Colors**: Edit the `:root` variables at the top of `styles.css` to change the color scheme.
