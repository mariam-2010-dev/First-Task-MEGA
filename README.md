# Portfolio using only HTML


## What is HTML?
HTML (Hyper Text Markup Language) is the standard language used to create and structure content on the web.


## W3C Validator
![W3C Validator Screenshot](assets/images/W3C%20Validator.png)


## Web site photos:
![My website screenshot](assets/images/Screenshot%202025-11-22%20105339.png)
![My website screenshot](assets/images/Screenshot%202025-11-22%20105421.png)


## HTML Entities Used
1- `&amp;`
2- `&nbsp`
3- `&quot`
4- `&lt;`
5- `&gt;`
6- `&rarr;`
7- `&darr;`
8- `&mdash;`
9- `&ndash;`
10- `&copy;`


## Why I Used `<dl>` instead of `<ul>`?
I used `<dl>` (Description List) for the Skills section because each skill has
**a title (term) and a description**. `<dl>` allows pairing each term (`<dt>`)
with its definition (`<dd>`), which is semantically correct.  
Using `<ul>` would only list items without distinguishing between the skill name and its description.



## Live Demo
[Live Site on GitHub Pages](https://mariam-2010-dev.github.io/my-dream-portfolio/)

---

## Project Overview
This project is an upgraded version of my Week 1 Personal Portfolio.  
It uses **pure CSS** (no Flexbox, no Grid, no frameworks) to create a colorful, professional, and responsive website showcasing my skills, experience, projects, and contact info.

---

## Screenshots

### Before CSS
![Before CSS](assets/images/ImagesBefore/Screenshot%202025-12-05%20015850.png)
![Before CSS](assets/images/ImagesBefore/Screenshot%202025-12-05%20015917.png)
![Before CSS](assets/images/ImagesBefore/Screenshot%202025-12-05%20015932.png)

### After CSS
![After CSS](assets/images/ImagesAfter/Screenshot%202025-12-05%20015952.png)
![After CSS](assets/images/ImagesAfter/Screenshot%202025-12-05%20020010.png)
![After CSS](assets/images/ImagesAfter/Screenshot%202025-12-05%20020041.png)
![After CSS](assets/images/ImagesAfter/Screenshot%202025-12-05%20020100.png)
![After CSS](assets/images/ImagesAfter/Screenshot%202025-12-05%20020125.png)
![After CSS](assets/images/ImagesAfter/Screenshot%202025-12-05%20020140.png)
![After CSS](assets/images/ImagesAfter/Screenshot%202025-12-05%20020151.png)

---

## Features & CSS Properties Used

| Property / Concept       | Used On                        | Example Value                         |
|--------------------------|--------------------------------|---------------------------------------|
| external CSS file        | Whole project                  | `<link rel="stylesheet" href="style.css">` |
| color / background-color | Header, Sections, Footer       | `background-color: #AE847E; color: #E2C290;` |
| background-image         | Hero section                   | `background-image: url('assets/bg.jpg');` |
| padding                  | Sections, containers           | `padding: 50px 20px;`                 |
| margin                   | Sections, elements             | `margin: 20px 0;`                     |
| border / border-radius   | Profile picture, buttons       | `border-radius: 50%; border: 4px solid #FCD0A1;` |
| outline                  | Focus state on links/buttons   | `outline: 2px solid #FCD0A1;`        |
| width / height / max-width | Images, containers           | `width: 350px; height: 350px;`       |
| display (block/inline/inline-block) | Skills list, nav links | `display: inline-block;`             |
| overflow                 | Sections with long text       | `overflow: hidden;`                   |
| visibility / display      | Hidden notes / elements      | `display: none;`                       |
| grouping selectors / nesting | nav ul li a, .home-img img | `.home-img img, header nav a`        |
| clean class names (BEM)   | Sections and elements        | `.home-txt, .about-txt, .home-img`  |