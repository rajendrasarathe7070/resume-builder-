# 📄 ResumeHub – Public & Private Edit Links

[![Made with](https://img.shields.io/badge/Made%20with-HTML%2FCSS%2FJS-blue)](https://developer.mozilla.org/)
[![LocalStorage](https://img.shields.io/badge/Storage-localStorage-green)](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage)
[![License](https://img.shields.io/badge/License-MIT-yellow)](LICENSE)

**ResumeHub** is a pure front‑end resume platform where anyone can create a resume, get a **public view link** (read‑only) and a **private edit link** (full editing). All data stays in your browser’s `localStorage` – no server, no database, no cost.

🔗 **Demo:** [Try it now](https://yourusername.github.io/resumehub/?user=alexmorgan) (replace with your live link)

---

## ✨ Features

- **Two links per resume**  
  - `?user=username` → Public, read‑only view (safe to share)  
  - `?edit_token=random` → Private, full editing access (keep secret)

- **Create new resumes** – anyone can sign up with a unique username.

- **Full‑data editing** – edit everything:  
  - Personal info (name, title, email, phone, location, GitHub)  
  - About me  
  - Section headings (About, Education, Experience, Skills, Certificates, Projects)  
  - Skills (with percentage bars)  
  - Certificates (name, issuer, year)  
  - Work experiences (title, company, date, bullet points)  
  - Projects (name, description, tech tags)

- **Search** users by username or full name – always opens the public view.

- **PDF export** – click the PDF button to print or save as PDF.

- **Permanent storage** – all data lives in your browser’s `localStorage`. Close the tab, restart the browser – your resumes stay safe.

- **No backend, no database** – 100% HTML/CSS/JS. Host it on GitHub Pages, Netlify, or any static server.

---

## 🚀 How to Use

1. **Open `index.html`** in any modern browser (Chrome, Firefox, Edge, Safari).

2. **Create a resume**  
   - Click the green **“New Resume”** button.  
   - Enter a unique username (e.g., `john_doe`), your full name, and email.  
   - Click **Create** – you’ll see an alert with your two links.

3. **Share your public link** – anyone can view your resume at `index.html?user=john_doe` (no edit button).

4. **Edit your resume** – open the **private edit link** (e.g., `index.html?edit_token=7f3a9b...`).  
   - Click the purple **Edit** button.  
   - Modify any field.  
   - Click **Save Changes** – your resume updates instantly.

5. **Search** for other users – use the search bar on the top bar.

6. **Download as PDF** – click the blue **PDF** button and use your browser’s print dialog.

---

## 📁 File Structure

---

## 🛠️ Technology Stack

| Layer       | Technology                      |
|-------------|---------------------------------|
| Markup      | HTML5                           |
| Styling     | Tailwind CSS + custom animations|
| Icons       | Lucide (via CDN)                |
| JavaScript  | Vanilla JS (ES6)                |
| Storage     | Browser localStorage            |
| Fonts       | Google Fonts (Inter)            |

---

## 🔐 Security & Privacy

- All data stays **on your device** – nobody else can access it unless they have your exact edit token.
- The edit token is generated randomly (`Math.random().toString(36)`).
- **Do not share your edit link** – anyone with that link can modify your resume.
- Public links are **read‑only** – no editing possible.

---

## 🧪 Local Development

1. Clone or download this repository.
2. Open `index.html` in your browser – no server needed.
3. Make changes – it’s all client‑side.

```bash
git clone https://github.com/yourusername/resumehub.git
cd resumehub
# open index.html in your browser
