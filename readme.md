<a name="readme-top">

<br/>

<br />
<div align="center">
  <a href="https://github.com/JigMenez/">
  <!-- TODO: If you want to add logo or banner you can add it here -->
    <img src="./assets/img/nyebe_white.png" alt="Nyebe" width="130" height="100">
  </a>
<!-- TODO: Change Title to the name of the title of your Project -->
  <h3 align="center">Heroes and Cards</h3>
</div>
<!-- TODO: Make a short description -->
<div align="center">
  Hello. This is my project for the Heroes and Cards code.
</div>

<br />

<!-- TODO: Change the zyx-0314 into your github username  -->
<!-- TODO: Change the WD-Template-Project into the same name of your folder -->
![](https://visit-counter.vercel.app/counter.png?page=JigMenez/WD-Hero-and-Card-Styles)

---

<br />
<br />

<!-- TODO: If you want to add more layers for your readme -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#overview">Overview</a>
      <ol>
        <li>
          <a href="#key-components">Key Components</a>
        </li>
        <li>
          <a href="#technology">Technology</a>
        </li>
      </ol>
    </li>
    <li>
      <a href="#rule,-practices-and-principles">Rules, Practices and Principles</a>
    </li>
    <li>
      <a href="#resources">Resources</a>
    </li>
  </ol>
</details>

---

## Overview

<!-- TODO: To be changed -->
<!-- The following are just sample -->
The project is about showcasing different hero and static card styles. In this code, we have a landing page with 2 buttons: the Hero Gallery and the Card Gallery. In the Hero Gallery, we are directed to the Hero Section, where we can see the heroes displayed. In the Card Gallery, we are directed to the Card Section, where we can see the different cards and the different animations it displays.


### Key Components
<!-- TODO: List of Key Components -->
<!-- The following are just sample -->
HTML Structure:

- index.html: The main landing page of your website. It includes:
  - Header section with title, subtitle, description, and navigation buttons.
  - Main content area where users can interact with hero and card displays.
  - Footer section for additional information or links.
- heroes/heroX.html: Pages displaying different hero styles. Each hero page includes:
  - Header with a link back to index.html.
  - Hero content such as images, titles, and descriptions specific to that hero style.
- card-gallery/animated-cards.html: Page displaying different animated card styles. Includes:
  - Header with a link back to index.html.
  - Card gallery section where animated cards are displayed with titles and descriptions.

Navigation Links:

- Links (<a> tags) within index.html to navigate to:
  - heroes/heroX.html for exploring different hero styles.
  - card-gallery/animated-cards.html for exploring animated card styles.
- Back links (<a> tags with href="../index.html") in hero and card pages to navigate back to index.html.

Main CSS (css/main.css):

- Defines global styles such as:
  - Font styles (font-family, font-size, etc.).
  - Background colors or images.
  - Overall layout (using flexbox, grid, or other layout techniques).
  - Styling for headers, paragraphs, buttons, and links.

Specific CSS for Hero Pages (css/hero.css):

- Styles specific to the hero pages, including:
  - Hero image sizes (max-width, height, etc.).
  - Text styles for hero titles and descriptions.
  - Layout adjustments for the hero content.

Specific CSS for Card Pages (css/card.css):

- Styles specific to the card pages, including:
  - Card layout (width, padding, margin, etc.).
  - Image styling for cards (border-radius, box-shadow, etc.).
  - Text styles for card titles and descriptions.

Animations CSS (css/animations.css):

- Contains keyframes (@keyframes) for different animations applied to cards.
- Each animation defines transitions or effects (transform, opacity, etc.) for cards to create engaging visual effects.

Other Components

- Fonts:
  - Link to Google Fonts (<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">) in index.html for consistent typography across the site.

- Images:
  - Store images for heroes (heroes/heroX.jpg) and cards (card-gallery/animated-cardX.jpg) in appropriate directories.
  - Use <img> tags with src attributes pointing to these image files within HTML pages.

- Responsive Design:
  - Implement CSS techniques (media queries, flexbox, grid, etc.) to ensure the website displays correctly on different devices and screen sizes.

- Deployment:
  - Deploy the website to a web hosting service (such as GitHub Pages, Netlify, etc.) to make it accessible online.






### Technology
<!-- TODO: List of Technology Used -->
![HTML](https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=white)

## Rules, Practices and Principles
1. Always use `WD-` in the front of the Title of the Project for the Subject followed by your custom naming.
2. Do not rename any .html files; always use `index.html` as the filename.
3. Place Files in their respective folders.
4. All file naming are in camel case.
   - Camel case is naming format where there is no white space in separation of each words, the first word is in all lower case while the succeding words first letter are in upper followed by lower cased letters.
   - ex.: buttonAnimatedStyle.css
5. Use only `External CSS`.
6. Renaming of Pages folder names are a must, and relates to what it is doing or data it holding.
7. File Structure to follow below.

```
WD-ProjectName
└─ assets
|   └─ css
|   |   └─ style.css
|   └─ img
|   |   └─ fileWith.jpeg/.jpg/.webp/.png
|   └─ js
|       └─ script.js
└─ pages
|  └─ pageName
|     └─ assets
|     |  └─ css
|     |  |  └─ style.css
|     |  └─ img
|     |  |  └─ fileWith.jpeg/.jpg/.webp/.png
|     |  └─ js
|     |     └─ script.js
|     └─ index.html
└─ index.html
└─ readme.md
```

## Resources

<!-- TODO: Add References -->
| Title | Purpose | Link |
|-|-|-|
| Heroes and Card STyles | To showcase the different heroes and static card styles while using landing pages. | [trykolang.com](https://jigmenez.github.io/WD-Hero-and-Card-Styles/) |
