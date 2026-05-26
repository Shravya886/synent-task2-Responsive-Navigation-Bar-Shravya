# Responsive Navigation Bar

A simple responsive navigation bar built using HTML, CSS, and JavaScript. This project demonstrates a mobile-friendly navbar with a hamburger menu and smooth scrolling between sections.

## Live Demo
 https://github.com/Shravya886/synent-task2-Responsive-Navigation-Bar-Shravya.git
 
## Project Description
This project is a fully responsive navigation bar that works on both desktop and mobile devices. 
It includes a logo, navigation links, and a hamburger menu for smaller screens. The navigation smoothly scrolls to different sections of the page including Home, About, Services, and Contact.

## Features
- Responsive navigation bar
- Logo and menu items
- Hamburger menu for mobile devices
- JavaScript toggle for menu open/close
- Smooth scrolling navigation
- Fixed navbar on top
- Click menu item to auto-close mobile menu

## Technologies Used
HTML, CSS, JavaScript

## Project Structure
responsive-navbar/
index.html
style.css
README.md

## How It Works
The HTML file contains the structure of the navbar and sections. CSS is used for styling, layout, and responsiveness using media queries. 
JavaScript is used to toggle the mobile menu when the hamburger icon is clicked. The navigation links use anchor tags with section IDs for smooth scrolling.

## JavaScript Code
const hamburger = document.querySelector(".hamburger");
const navLinks = document.querySelector(".nav-links");

hamburger.addEventListener("click", () => {
  navLinks.classList.toggle("active");
});

## Sections Included
Home, About, Services, Contact

## Learning Outcomes
This project helped in understanding responsive design, flexbox layout, media queries, and basic JavaScript DOM manipulation.

## Author
Shravya Mididoddi
