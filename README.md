# 📰 TechNews - Technology News Portal

![TechNews Preview](./assets/images/Image%2001.png)

> **Project Status:** Completed ✅

## 💻 About the Project

**TechNews** is a high-fidelity, responsive news portal focused on the latest digital trends. This project was developed as a technical challenge to master complex layouts using **CSS Grid** and **Flexbox**, strictly following the professional design system provided by Rocketseat.

The site features an advanced content organization, including robotics highlights, AI sections, weekly news, and a dedicated sidebar for advertisements and extra content.

---

## 🚀 Key Features

* **Advanced Grid System**: Full implementation of `grid-template-areas` to manage the high-level site structure.
* **Mosaic Header**: A dynamic highlight section featuring 1 primary news story and 4 secondary stories.
* **Modular CSS Architecture**: Clean code organization divided into `global.css`, `utility.css`, `header.css`, and `sections.css`.
* **Responsive Design**: Mobile-first approach ensuring readability across all devices.
* **Interactive UI**: Smooth hover transitions, scaling effects, and accessible navigation.

---

## 🛠 Technologies Used

* **HTML5**: Semantic markup for SEO and accessibility.
* **CSS3**:
    * **Grid Layout**: For the main structural "map" and mosaic sections.
    * **Flexbox**: For navigation bars and internal element alignment.
    * **Variables (Design Tokens)**: Centralized management of colors, typography, and spacing.
* **Google Fonts**: Implementation of the *Archivo* font family.

---

## 📐 Structural Blueprint (Grid Map)

The main layout was orchestrated using the following CSS Grid configuration:

```css
grid-template-areas: 
    "featured featured"
    "weekly   weekly"
    "ai       aside";
