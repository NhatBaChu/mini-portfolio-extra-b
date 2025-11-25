[README_ExtraB.md](https://github.com/user-attachments/files/23745724/README_ExtraB.md)
# Personal Web Portfolio (Extra-B)

## 1. Overview
This is a multi-page **static personal portfolio website** created for the Mini‑Portfolio Extra‑B task.  
The site introduces me, showcases my projects, highlights my skills, and provides contact information.  
It follows a light theme with a single blue accent color and includes small JavaScript interactions.

**Student:** Nguyễn Lương Nhật  
**Student ID:** AUS14988  
**Email:** luongnhat31012007@gmail.com  
**GitHub:** https://github.com/NhatBaChu

---

## 2. Folder Structure
```
PERSONAL_PORTFOLIO/
│
├── index.html
├── about.html
├── projects.html
├── contact.html
│
├── css/
│   └── style.css
│
├── js/
│   └── main.js
│
└── assets/
    ├── avatar.jpg
    ├── hero-bg.jpg
    ├── project1.jpg
    ├── project2.jpg
    └── project3.jpg
```

---

## 3. Pages
- **Home (index.html)**  
  Hero section with nature background, white overlay card (name, intro, buttons), and avatar.

- **About (about.html)**  
  Full about content inside one large white card. Includes quick info, education, skills, and goals.

- **Projects (projects.html)**  
  Shows 3 projects in styled cards with images, descriptions, and tech tags.

- **Contact (contact.html)**  
  Contact details + simple contact form with JavaScript validation.

---

## 4. Features Implemented
### HTML / CSS
- Semantic layout (`header`, `nav`, `main`, `section`, `footer`)
- Consistent navbar across all pages
- Light theme UI:
  - Background: `#F3F4F6`
  - Cards: `#FFFFFF`
  - Text main: `#111827`
  - Text secondary: `#6B7280`
  - Accent: `#2563EB`
- Responsive design using **Grid/Flexbox** + media queries
- Card hover effects (lift + shadow)
- Subtle geometric dot pattern at top‑left and bottom‑right

### JavaScript (js/main.js)
- **Active navbar highlight** based on current page
- **Back-to-top button** appears on scroll and smooth scrolls to top
- **Contact form validation** (alerts empty fields, shows success message)

---

## 5. How to Run
### Requirements
- Any modern web browser (Chrome / Edge / Firefox)
- VS Code (recommended)

### Run locally
1. Open the project folder in VS Code.
2. Open `index.html`.
3. Use one of these:
   - **Go Live (Live Server)** to preview with auto‑reload  
   - Or open `index.html` directly in your browser.

---

## 6. Deployment (GitHub Pages)
If deployed, the live site is available here:

**GitHub Repository:** *(replace with your Extra‑B repo link)*  
`https://github.com/NhatBaChu/<your-extra-b-repo>`

**GitHub Pages:** *(replace after enabling Pages)*  
`https://nhatbachu.github.io/<your-extra-b-repo>/`

---

## 7. Testing
Tested successfully:
- Navigation links between pages
- Responsive layout on mobile width
- Hero background and overlay card render correctly
- Cards hover smoothly
- JavaScript functions:
  - Active menu highlight
  - Back‑to‑top button
  - Contact form validation

Screenshots are included in the Extra‑B report PDF.

---

## 8. Author
Nguyễn Lương Nhật — AUS14988  
Mini‑Portfolio Extra‑B (2025)
