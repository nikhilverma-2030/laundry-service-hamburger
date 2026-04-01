# Laundry Service Hamburger Menu

This hamburger menu is designed using pure HTML and CSS, without relying on JavaScript. It uses the :focus pseudo-class to toggle the visibility of the navigation menu, allowing users to open and close it by interacting with the hamburger icon. The menu is fully responsive, and the hamburger icon appears only on smaller (mobile) screens using media queries.

## Features

-> Responsive design for desktop and mobile screens
-> Hamburger menu appears only on small screen devices
-> Navigation menu opens using the ':focus' pseudo-class
-> Clean and simple UI layout
-> Flexbox used for layout alignment

## How It Works

-> The hamburger button is hidden on larger screens using CSS.
-> On mobile screens (max-width: 600px), the hamburger icon becomes visible.
-> When the user focus on the hamburger button, the ':focus' pseudo-class is triggered.
-> Using the selector '.hamburger:focus + .menu', the menu slides right into left view.

## Technologies Used

-> HTML5
-> CSS3 (Flexbox, Media Queries, Pseudo-classes)

## Files

-> 'index.html' → Main HTML file
-> 'style.css' → Styling file

# Sections in the Webpage

Navbar

The navigation bar contains:

-> Logo on the left
-> Navigation links in the center (Home, Services, About Us, Contact Us) for the large screen size.
-> When we open the page in the small size screen like mobile phones then navigation links in the hamburger icon    will be on the right corner of the screen.
-> Username button on the right

## Key Concepts Used

-> Flexbox for layout
-> Media queries for responsiveness
-> ':focus' pseudo-class for interaction
-> CSS transitions for smooth animation

## Usage

1. Open the project in a browser.
2. Resize the screen to mobile size.
3. Click on the hamburger icon to open the menu.

## Aurthor
Nikhil Verma
