# Musa Sahin - Interactive Developer CV

This is a personal CV/Resume website built with HTML, CSS, and JavaScript. It features a modern, responsive design and a client-side PDF generation capability.

## Features

- **Responsive Design:** Optimized for desktop, tablet, and mobile viewing.
- **Premium UI:** Custom styled header, clean typography (Inter font), and categorized skills section.
- **PDF Generation:** Includes a "Download PDF" button that generates a high-quality, single-page PDF of the CV directly in the browser using `html2pdf.js`.
- **ATS Friendly:** Semantic HTML structure.

## Structure

- `index.html`: Main content and layout structure.
- `style.css`: All styling, including the custom "Header Centered" premium theme.
- `html2pdf.js`: Integrated via CDN for PDF conversion functionality.

## How to Edit

1. Open `index.html` to update your personal information, experience, or education.
2. Edit `style.css` to change colors, fonts, or spacing.
3. The PDF button configuration is located at the bottom of `index.html` in the `<script>` tag.

## 🚀 Deployment (Root Domain)

To publish at **`https://musahinist.github.io`** (without `/resume` at the end):

1.  **Repository Name:** You must create a repository named exactly **`musahinist.github.io`**.
2.  **Push Code:**
    ```bash
    git init
    git add .
    git commit -m "Initial commit"
    git branch -M main
    # Ensure the repo URL matches your username.github.io pattern
    git remote add origin https://github.com/musahinist/musahinist.github.io.git
    git push -u origin main
    ```
3.  **Activate Pages:**
    - Go to Repository **Settings** > **Pages**.
    - Select Source: **Deploy from a branch** (Branch: `main`, Folder: `/`).
    - Save.

🎉 Your CV will be live at: `https://musahinist.github.io`


