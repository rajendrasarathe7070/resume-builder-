
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
