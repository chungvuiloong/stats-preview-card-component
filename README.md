# Frontend Mentor - Stats preview card component

![Design preview for the Stats preview card component coding challenge](./design/desktop-preview.jpg)

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size

### Screenshot


### Links

- Solution URL: [Github](https://github.com/chungvuiloong/stats-preview-card-component)
- Live Site URL: [Vercel](https://mrjays-stats-preview-card-component.vercel.app/)

## My process
Starting with mobile first approach, I analyse both the designs in mobile and desktop view. By doing, I can understand the structure better and design a layout that suits adjusts according in both mobile and desktop.

- There are two sections.
    - Text Content
        - Flex-cols: 
    - Image
    - Footer
- Container will hold both Textcontent & Image.
    - Desktop view: Flex-row
    - Mobile view: Flex-col

### Built with

- Semantic HTML5 markup
- [TailwindCSS](https://tailwindcss.com/)
- Flexbox
- Mobile-first workflow

### What I learned

This project was used so I can better learn to add custom css variables to html via cdn. By doing, I learned how to better code custom variables such as:

```
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=Lexend+Deca&display=swap" rel="stylesheet">

  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
        theme: {
                    extend: {
                        fontFamily: {
                            Inter: ['Inter', 'sans-serif'],
                            'Lexend-Deca': ['Lexend Deca', 'sans-serif']
                        },
                        colors: {
                            // Primary
                            'Very-dark-blue': 'hsl(233, 47%, 7%)',
                            'Dark-desaturated-blue': 'hsl(244, 38%, 16%)',
                            'Soft-violet': 'hsl(277, 64%, 61%)',

                            // Neutral
                            White: 'hsl(0, 0%, 100%)',
                            'Slightly-transparent-white-p': 'hsla(0, 0%, 100%, 0.75)',
                            'Slightly-transparent-white-h': 'hsla(0, 0%, 100%, 0.6)',
                      }
                  }
        }
    }
```

### Continued development

This component can be further developed with different structure. And reused for another project.

## Author

- Website - [MrJay's Simple Portfolio](https://mrjays-simple-portfolio.vercel.app/)
- Github - [Jere/ Chung Vui Loong](https://github.com/chungvuiloong)
