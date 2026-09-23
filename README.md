# Vigneswar T - Personal DevOps & Cloud Portfolio

A modern, high-performance portfolio website inspired by the iconic **Tomasz Gajda Figma design**, tailored specifically for **Vigneswar T (DevOps & Cloud Engineer)**.

The website is built with clean **semantic HTML5, modern CSS3, and vanilla JavaScript**, fully responsive across all screen sizes, and optimized for instant, zero-configuration hosting on **GitHub Pages**.

---

## 🎨 Theme & Color Palette
Extracted directly from your profile photo:
- **Primary Color (Burgundy / Wine)**: `#8A1C36` — matching your blazer
- **Accent Color (Crimson Rose)**: `#C73860` & `#E24874` — for active buttons, badges, glowing borders, and icons
- **Slate Lavender**: `#8E98C2` — matching the studio backdrop
- **Canvas / Background**: `#0B0C12` (Obsidian) & `#10121B` (Dark Glass Cards)
- **Typography**: Google Fonts *Inter* & *Outfit*

---

## 📁 File Structure

```text
vigneswar-portfolio/
│
├── index.html        # Complete semantic HTML structure & all content
├── style.css         # Custom styling, dark mode, glassmorphism, responsive queries
├── script.js         # Navigation, project filtering, email clipboard copy, form handling
├── README.md         # Deployment & customization guide
└── assets/
    ├── profile.jpg   # Your uploaded profile photograph
    ├── resume.pdf    # Your uploaded PDF resume (linked to "Download Resume")
    └── icons/        # Official vector SVG brand icons (AWS, Azure, Docker, etc.)
```

---

## 🚀 How to Deploy Directly to GitHub Pages

### Method 1: Host at `https://yourusername.github.io` (Recommended)
1. Go to [GitHub](https://github.com/) and click **New Repository**.
2. Set the repository name to:
   ```text
   yourusername.github.io
   ```
   *(Replace `yourusername` with your actual GitHub username, e.g., `Vulcan-14.github.io`)*
3. Make sure the repository is **Public**.
4. In your new repository page, click **uploading an existing file**.
5. Drag and drop all files from this folder (`index.html`, `style.css`, `script.js`, `README.md`, and the `assets` folder with `profile.jpg` and `resume.pdf`).
6. Click **Commit changes**.
7. Within 1 to 2 minutes, your website will be live at:
   `https://yourusername.github.io`

### Method 2: Host from a Named Repository (e.g., `portfolio`)
1. Create a repository named `portfolio`.
2. Push or upload the files.
3. Go to **Settings** > **Pages** in your repository.
4. Under **Branch**, select `main` (or `master`) and folder `/ (root)`, then click **Save**.
5. Your site will be live at `https://yourusername.github.io/portfolio/`.

---

## ✏️ How to Easily Update Your Content Anytime

All content is cleanly organized in `index.html` with explicit section comments:

| Section to Update | Where to edit in `index.html` |
|---|---|
| **Profile Photo** | Replace `assets/profile.jpg` with a new image (keep name `profile.jpg` or update line 133). |
| **Resume PDF** | Replace `assets/resume.pdf` with your newest PDF resume. |
| **About Me** | Search for `<!-- ==================== ABOUT ME SECTION ==================== -->` around line 150. |
| **Skills & Technologies** | Search for `<!-- ==================== SKILLS SECTION ==================== -->` around line 245. |
| **Experience / Jobs** | Search for `<!-- ==================== EXPERIENCE SECTION ==================== -->` around line 380. |
| **Projects** | Search for `<!-- ==================== PROJECTS SECTION ==================== -->` around line 485. |
| **Certifications** | Search for `<!-- ==================== CERTIFICATIONS & EDUCATION ==================== -->` around line 620. |
| **Contact Info & Socials** | Search for `<!-- ==================== CONTACT SECTION ==================== -->` around line 700. |

---

## 💻 Local Testing
You can preview the website locally anytime:
```bash
# If using Python:
python -m http.server 8080

# Or if using Node.js:
npx serve .
```
Then visit `http://localhost:8080` in your web browser.
