# 🏙️ NovaPolis - Smart City Web Portal

A modern, attractive, and fully responsive **Smart City Website** built strictly using **HTML5 and CSS3** (No JavaScript, No Frameworks like Bootstrap or React). 

Created specifically for a **B.Tech 1st Year Engineering Project submission** and ready to push to **GitHub** and publish on **GitHub Pages**.

---

## 🌟 Key Features

- **100% Pure HTML5 & CSS3**: No JavaScript, No jQuery, No Bootstrap, No external libraries.
- **Pure CSS Responsive Hamburger Menu**: Fully functional mobile menu drawer using the CSS checkbox toggle technique without a single line of JavaScript.
- **Modern Color Palette**: Professional blue (`#2563eb`), vibrant eco-green (`#10b981`), and clean crisp white (`#ffffff`).
- **Interactive Card Hover Effects**: Elevated 3D transforms (`translateY`), smooth shadow expansions, and subtle image zoom transitions.
- **CSS Grid & Flexbox**: Modern, clean, and flexible responsive layouts that look great on smartphones, tablets, laptops, and desktop screens.
- **Smooth Navigation**: HTML anchor links with CSS smooth scrolling (`scroll-behavior: smooth`).
- **Emergency Priority Section**: High-contrast, dark-mode emergency hotline hub with instant `tel:` phone links for Police (112), Ambulance (108), Fire (101), and civic safety helplines.
- **Beginner-Friendly Code**: Thoroughly commented code structure that is simple to understand, customize, and explain during college viva/lab presentations.

---

## 📑 Website Sections

1. **Navigation Bar**: Sticky glassmorphic navbar with custom Smart City SVG logo, section navigation links, emergency pill badge, and mobile hamburger menu.
2. **Hero Section**: Full-screen city skyline hero banner with gradient overlay, live pulse indicator, subtitle, and primary/secondary Call-to-Action (CTA) buttons.
3. **City Statistics**: 4 visual metric cards showing population (2.8M+), smart hospitals (45+), electric buses (1,250+), and digital schools (380+).
4. **Smart Transportation**: Cards highlighting Metro Rail Expressway, Green EV Buses, and AI Adaptive Traffic Grid with route details.
5. **Healthcare & Hospitals**: Information on Multi-Speciality Medical Hubs, Digital Telemedicine OPD, and GPS-guided Smart Ambulance Fleets.
6. **Education & Smart Schools**: Interactive smart classrooms, Metropolitan Tech University, and Digital Public Library Hubs.
7. **Public Services**: One-stop e-Governance portal, Smart Water & Automated Sanitation grid, and Rooftop Solar/Clean Energy networks.
8. **Emergency Hotlines**: Toll-free instant emergency cards for **Police (112)**, **Ambulance (108)**, **Fire (101)**, plus secondary helplines (Women safety 1091, Child helpline 1098, Disaster 1077, Traffic 1095).
9. **Key City Locations**: Detailed cards for CyberTech Silicon Hub, Central Town Hall & Civic Plaza, and Nova Lakefront Eco-Park with metadata and amenity tags.
10. **Citizen Helpdesk & Contact**: Full HTML5 form with field validation (Name, Email, Phone, Department, Message, Consent) and municipal office contact info.
11. **Footer**: 4-column footer with brand statement, navigation directory, civic services links, emergency quick dial, social media links, and B.Tech project credits.

---

## 📁 Project Structure

```text
City/
│
├── index.html            # Main semantic HTML5 webpage
├── style.css             # Main CSS3 stylesheet (Grid, Flexbox, Animations)
├── README.md             # Project documentation & GitHub push guide
│
└── images/               # High-resolution local image assets
    ├── hero-city.jpg     # City skyline hero background
    ├── metro.jpg         # Metro transit train
    ├── bus.jpg           # Green electric city bus
    ├── traffic.jpg       # Smart traffic command center
    ├── hospital.jpg      # Multi-speciality hospital
    ├── telemedicine.jpg  # Digital doctor consultation
    ├── emergency.jpg     # Ambulance paramedic unit
    ├── school.jpg        # Digital smart classroom
    ├── university.jpg    # University campus
    ├── library.jpg       # Modern digital library
    ├── services.jpg      # e-Governance municipal desk
    ├── water-grid.jpg    # Clean water & sanitation grid
    ├── green-energy.jpg  # Solar panels and wind power
    ├── techpark.jpg      # Cyber city IT tech park
    ├── civic.jpg         # Civic center and town hall
    └── ecopark.jpg       # Lakefront eco park
```

---

## 🚀 How to Run the Website Locally

1. Open File Explorer and navigate to `C:\Users\ramge\Downloads\City`.
2. Double-click on `index.html` (it will open in Google Chrome, Microsoft Edge, or Firefox).
3. The website will load completely with all images, hover effects, and responsive navigation offline.

---

## 🌐 Step-by-Step Guide: How to Push to GitHub & Enable GitHub Pages

Follow these simple steps in **Terminal** or **PowerShell** to upload this project to your GitHub account:

### Step 1: Open Terminal in Project Directory
Open PowerShell or Command Prompt, then type:
```bash
cd "C:\Users\ramge\Downloads\City"
```

### Step 2: Initialize Git Repository
```bash
git init
git add .
git commit -m "Initial commit: NovaPolis Smart City Website (HTML5 & CSS3)"
```

### Step 3: Create a Repository on GitHub
1. Go to [github.com](https://github.com) and log in.
2. Click the **+** (plus) icon in the top right corner and choose **New repository**.
3. Name your repository (e.g., `smart-city-website` or `novapolis-smart-city`).
4. Keep it **Public**.
5. Do **NOT** check "Add a README file" (we already created one).
6. Click **Create repository**.

### Step 4: Link Local Repository to GitHub and Push
Copy the commands shown on GitHub or run:
```bash
git branch -M main
git remote add origin https://github.com/<YOUR_GITHUB_USERNAME>/<YOUR_REPOSITORY_NAME>.git
git push -u origin main
```
*(Replace `<YOUR_GITHUB_USERNAME>` and `<YOUR_REPOSITORY_NAME>` with your real GitHub username and repository name).*

### Step 5: Enable GitHub Pages (Free Live Website URL)
1. On your GitHub repository page, click on **Settings** (tab at the top).
2. On the left sidebar, click on **Pages**.
3. Under **Build and deployment** -> **Branch**:
   - Select **`main`** branch from the dropdown.
   - Leave the folder as **`/(root)`**.
   - Click **Save**.
4. Wait 1 to 2 minutes, refresh the page, and GitHub will provide you with a live link:
   `https://<YOUR_GITHUB_USERNAME>.github.io/<YOUR_REPOSITORY_NAME>/`

---

## 🎓 Viva & Presentation Q&A (For B.Tech 1st Year Students)

Here are common questions faculty ask during web design evaluations:

1. **How did you build a mobile menu without JavaScript?**
   - *Answer*: Using the **CSS Checkbox Hack**. A hidden `<input type="checkbox" id="nav-toggle">` is controlled by a `<label for="nav-toggle">` hamburger icon. In CSS, we use the sibling combinator (`#nav-toggle:checked ~ .nav-menu`) to expand or collapse the menu.
2. **What layout techniques were used?**
   - *Answer*: **CSS Flexbox** was used for 1-dimensional layouts (navbars, headers, card contents, button groups). **CSS Grid** (`repeat(auto-fit, minmax(...))`) was used for 2-dimensional layouts (responsive stats grid, 3-column service cards, contact layout).
3. **How does smooth scrolling work?**
   - *Answer*: By adding `scroll-behavior: smooth;` to the `html` selector in CSS. Clicking any anchor tag (`<a href="#section-id">`) smoothly animates the viewport to that section.
4. **How are images organized?**
   - *Answer*: All images are kept locally inside the `images/` directory with relative paths (`images/filename.jpg`) so the site functions both offline on localhost and online on GitHub Pages without broken links.

---

### 👨‍💻 Author
- **Course**: B.Tech 1st Year Engineering
- **Subject**: Web Technologies / Engineering Workshop Project
- **License**: MIT License (Open Source)
