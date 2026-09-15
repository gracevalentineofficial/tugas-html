# Grace Valentine's Personal Website

An interactive personal website built using pure HTML without CSS. Ready and very easy to deploy directly to GitHub Pages.

---

## Key Features

### 1. Simple Navigation:
* Clean navigation bar with links to Home, About, Projects, Contacts, and Blogs.
* Built using basic HTML structural elements.

### 2. Category-Based Blog Layout:
* Blog posts grouped by categories (e.g., Digital Literacy, Information Systems, Database Systems).
* Displayed using pure HTML tables and centered alignment for a clean layout.

### 3. Under Development Redirection:
* Links on blog images and titles redirect users to a dedicated "Under Development" (`blog_belum_jadi.html`) page.

### 4. Pure HTML Design:
* Minimalist layout built entirely with core HTML tags (`<table>`, `<center>`, `<font>`, `<a>`).
* No CSS or JavaScript dependency.

---

## File Structure

```text
tugashtml_Grace Valentine_3C/
│
├── asset/                    # Folder for images and media files
├── about.html                # About page detailing personal profile
├── blog_belum_jadi.html      # Temporary page for blog posts under development
├── contacts.html             # Contact information page
├── home.html                 # Additional home page content
├── index.html                # Main homepage structure & entry point
├── projects.html             # Showcase of personal projects
└── README.md                 # Project documentation & GitHub Pages deployment guide
```

## GitHub Pages Deployment Guide
Follow these simple steps to upload and publish this website to GitHub Pages:

Step 1: Create a New Repository on GitHub
Open GitHub and log in to your account.

Click the New Repository button (or the + icon at the top right).

Name your repository (e.g., tugas-html).

Step 2: Push Your Local Code
Open your terminal in VS Code and run:

Bash
git add .
git commit -m "Initial commit"
git push -u origin main
Step 3: Enable GitHub Pages
Go to your repository Settings on GitHub.

Navigate to the Pages menu on the left sidebar.

Under Build and deployment -> Branch, select main and set the folder to /(root).

Click Save and wait 1–3 minutes for your site to go live!
