# Matéo Ginisty - Private Car Collection Management Website
## 1. Overview
This project is a single-page, responsive website for Matéo Ginisty,
showcasing his expert services in the curation and management of
private automobile collections. The website aims to provide a
professional and luxurious online presence, detailing his approach,
services, and providing a means for potential clients to make contact.
## 2. Technologies Used
* HTML5: For the structure and content of the website.
* CSS3: For styling, layout, animations, and responsive design.
Key features include:
* Flexbox for layout.
* CSS Transitions and Animations.
* ‘backdrop-filter‘ for "glassmorphism" effect.
* Media Queries for responsiveness.
* JavaScript (ES6+): For dynamic interactivity, including:
* DOM manipulation.
* Scroll-triggered animations and background changes.
* Event handling.
* Floating label effects for form inputs.
* Google Fonts: "Oswald" font.
* Formspree.io: For handling contact form submissions.
## 3. Project Structure
.
+-- assets/
| +-- index.jpg # Hero background image
| +-- section1.jpg # Background for services/approach
| +-- section2.jpg # Background for contact/lower page
+-- index.html # Main HTML file
+-- style.css # CSS stylesheet
+-- script.js # JavaScript file
## 4. How to View / Interact
1. Prerequisites: A modern web browser (e.g., Chrome, Firefox,
Safari, Edge).
2. Running Locally:
* Download or clone all project files (‘index.html‘, ‘style.css‘,
‘script.js‘, and the ‘assets‘ folder) into a single directory
15
on your local machine.
* Ensure the ‘assets‘ folder and its image contents are present
relative to ‘index.html‘.
* Open the ‘index.html‘ file in your web browser.
3. Interacting with the Website:
* Initial View: The website opens with a hero section. The main
content below is initially hidden.
* Reveal Content: Scroll down with your mouse wheel, trackpad,
or use touch scroll on a mobile device. This first interaction
will reveal the main content sections, the sticky header, and
the sticky footer.
* Navigation: The website is a single page. Continue scrolling
to view different sections:
* "Mon approche" (My Approach)
* "Mes services sur-mesure" (My Tailored Services)
* "Discutons de votre collection" (Let’s Discuss Your
Collection - Contact Form)
* Dynamic Backgrounds: As you scroll, notice the background
images transitioning smoothly between sections.
* Contact Form:
* Located in the "Discutons de votre collection" section.
* Fields with an asterisk (*) are notionally required (HTML5
validation handles this).
* Floating labels will animate as you type in the fields.
* Fill in your details and select your preferences.
* Click the "Soumettre la demande" (Submit Request) button.
* Upon successful submission, you will be redirected to a
Formspree confirmation page. If there are errors (e.g.,
invalid email format), HTML5 validation messages will appear.
* Responsive Design: Resize your browser window or view on
different devices (desktop, tablet, mobile) to see the layout
adapt.
## 5. Key Features Implemented
* Single-Page Application (SPA) feel: Smooth scrolling and content flow.
* Hero Section with Animation: Engaging initial presentation.
* Scroll-triggered Animations: Dynamic background transitions,
header/footer appearance.
* "Glassmorphism" UI: Semi-transparent content cards with blurred
backgrounds.
* Responsive Design: Adapts to various screen sizes.
* Interactive Contact Form: With floating labels and Formspree
integration.
* Sticky Header and Footer: For persistent navigation/branding and
contact info.

## 6. Report Link
https://github.com/TrysRelife/DIP392-TheFrenchies/blob/main/report_software.pdf

## 7. Video Presentation Link
https://www.youtube.com/watch?v=R5wnpwkHUwc
