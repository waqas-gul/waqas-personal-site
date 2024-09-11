# Personal Portfolio Website

This repository contains the source code and files for my personal portfolio website. The website is built using HTML, CSS, and JavaScript.

## Description

The personal portfolio website showcases my skills, projects, and experiences as a web developer. It serves as an online platform to highlight my work and provide information about my background and expertise.

### Prerequisites

Before you begin, ensure you have met the following requirements:

- You Should Know Basic or Intermediate of HTML ,CSS and JavaScript
- This website is developed by bootstrap 5 copy below code :

```
<!--- Bootstrap 5 css CDN Link --->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-rbsA2VBKQhggwzxH7pPCaAqO46MgnOM80zW1RWuH61DGLwZJEdK2Kadq2F9CUG65" crossorigin="anonymous" />

<!-- bootstrap javascript cdn link  -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-kenU1KFdBIe4zVF0s0G1M5b4hcpxyD9F7jL+jjXkk+Q2h455rYXK/7HAuoJl+0I4" crossorigin="anonymous"></script>
```

- JQuery CDN LInk :

```
<!-- JavaScript jQuery CDN -->
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.4/jquery.min.js"></script>
```

- Bootstrap Icon :

```
<!-- bootstrap icon cdn link  -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.4/font/bootstrap-icons.css"/>
```

### AOS Animation Library Installation

### Basic

Add Styles in `<head>` :

```css
<link rel="stylesheet" href="https://unpkg.com/aos@next/dist/aos.css" />
```

Add script right before closing `</body>` tag, and initialize AOS :

```js
<script src="https://unpkg.com/aos@next/dist/aos.js"></script>
<script>
  AOS.init();
</script>
```

### Using package managers

Install `aos` package:

- `yarn add aos@next`
- or `npm install --save aos@next`

Import script, styles and initialize AOS:

```js
import AOS from "aos";
import "aos/dist/aos.css"; // You can also use <link> for styles
// ..
AOS.init();
```

In order to make it work you'll have to make sure your build process has configured styles loader, and bundles it all correctly.
If you're using [Parcel](https://parceljs.org/) however, it will work out of the box as provided.

### How to use it ?

1. Initialize AOS :

```js
// initializing AOS library
AOS.init({
  duration: 1000,
  offset: 50,
});
```

2. Set animation using `data-aos` attribute:

```
<div data-aos="fade-in"></div>
```

### Project Contain

- Sticky Responsive Navigation Bar
- Hero Section
- Expertise section
- Skill Section with Progress Animation
- Working Portfolio Section
- Testimonial Section
- Blog Section
- Contact Section
- Footer Section
- Fully Responsive for all devices

### Font Family

- I have Used Google Fonts - Josefin Sans

```
<!-- google font link -->
<link rel="preconnect" href="https://fonts.googleapis.com" />
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
<link href="https://fonts.googleapis.com/css2?family=Josefin+Sans:wght@300;400;500;600;700&display=swap" rel="stylesheet"/>
```

### License

This project is **Free To Use** and does not contains any license.
