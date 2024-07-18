
## CODTHECH-Task1

- Name :JAMI KARTHIKEYA
- ID:CT4FWD3930
- Domain:FRONTEND WEB DEVELOPMENT
- Duration: July to August 2024
- Mentor: Neela Santhosh Kumar

# Project Title

PERSONAL PORTFOLIO WEBSITE

# Overview of the project
## HTML Structure

**Document Type Declaration:**<!DOCTYPE html> specifies the version of HTML being used.

**HTML Root:** The main HTML element with lang="en" indicates the language of the document.

**Head Section:** Contains important metadata like character encoding (charset="UTF-8"),viewport settings (<meta name="viewport" content="width=device-width, initial-scale=1.0"> for responsive design), and the website title (<title>)..

**Links:** It includes links to external resources such as a CSS file (style.css) for styling and Font Awesome (all.min.css) for icons.

## Body Structure

**Protfolio-container:** This is the main container for the entire portfolio website, ensuring it fills the entire viewport height (min-height: 100vh) and uses flexbox for layout.

**Navigation (navlist):**) A horizontal list (ul) styled as a navigation menu with links to different sections (HOME, WORK, ABOUT, PROJECT, SERVICES). The active class indicates the current page.

**Left-container:** The main content area on the left side, styled with a dark background (#262525) and containing:

**Social Icons (icons):** Links to social media profiles (Instagram, LinkedIn, Twitter, GitHub).

**Content (content):**): Introduction (Hi! I am Jami Karthikeya), heading (Web Developer.), details about the person's background, and buttons (Hire me, View project).

**Right-container:** Currently empty in the provided code but could potentially hold additional content in a future iteration.

**Design:** Decorative elements consisting of two circles with specific styling (background gradients and an image).

## CSS Overview 

**Global Styles:** Resets default margin and padding (margin: 0; padding: 0;), ensures all elements use the box model correctly (box-sizing: border-box), and sets the font family to 'Poppins' from Google Fonts.

**Layout Styling:** Uses flexbox (display: flex) extensively for responsive layout management. Elements like .protfolio-container, .navlist, .left-container, and .right-container are styled to occupy specific portions of the screen (width percentages) and maintain alignment.

**Content Styling:** Icons (icons class) styled to be vertically aligned with a gap between them (gap: 3rem).

Text (content) styled with specific fonts, sizes, and colors for readability and aesthetics (color, font-size).

Buttons styled with borders, padding, and transitions for interactive effects (border, padding, transition).

**Design Details:** Uses gradients (linear-gradient) and specific color codes (#262525, #3877ff, #5db9ee) to maintain a consistent visual theme.

**Hover effects (:hover)** on buttons and icons provide visual feedback to user interactions.

**Accessibility:** Ensure text contrast (color vs. background) is sufficient for readability, especially on hover effects.

**SEO:** Enhance SEO by adding more descriptive metadata (<title>, <meta> tags) and optimizing content for search engines.

**Responsiveness:** Test across various devices (desktops, tablets, mobile phones) to ensure the layout adjusts well (media queries may be useful).

**Performance:** Optimize images and other assets (image1.jpg referenced in CSS) for faster loading times and a smoother user experience.



