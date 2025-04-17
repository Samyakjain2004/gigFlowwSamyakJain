# gigFlowwSamyakJain

This HTML document is structured to display a webpage featuring testimonials with a dynamic slideshow. Here's a breakdown of its key features and elements:

Key Features:
Video Background:

The background of the page is a full-screen video that plays automatically, is muted, and loops.

The video-background class ensures the video covers the entire page, while its z-index is set to -1, ensuring it stays behind other content.

Light/Dark Theme Toggle:

A button in the top right corner toggles between light and dark modes.

The toggleTheme() JavaScript function changes the page's background (--bg) and text colors (--text) using CSS custom properties (variables).

Text Animation:

The "What People Say About Gigfloww" title uses a typewriter effect (typewriter class) that animates the text letter by letter, along with a blinking caret effect.

Swiper Slider:

The page features a Swiper carousel to display the testimonials. Swiper is a popular JavaScript library for creating touch sliders and carousels.

The slider (swiper) is set up with navigation arrows (swiper-button-next, swiper-button-prev) to allow users to navigate between testimonial slides.

Each slide has a testimonial with the text of a quote, the name of the author, and their avatar. The cards (swiper-slide) have a blurred background effect and a subtle hover transformation to make them interactive.

Styling:

The page is styled with custom CSS variables, which allows easy switching between dark and light themes.

The text uses a clean and modern font (Segoe UI), and all elements are aligned to create a balanced, centered layout.

Swiper slides have a hover effect (transform: rotateY(5deg) rotateX(5deg)) for a 3D interaction, giving them a more dynamic look.

CSS Variables (Root Custom Properties):
The use of custom properties like --bg, --text, --accent, etc., allows for easy theme switching and consistent styling across the page.

JavaScript Functionality:
Swiper JS: It initializes the Swiper slider with options for looping the slides, setting an autoplay delay, and defining the navigation controls.

Toggle Theme Function: The toggleTheme() function switches the page's theme between light and dark by modifying CSS variables directly.

HTML Structure:
Video Element: The <video> tag embeds the background video. It’s set to autoplay, mute, and loop for an engaging experience.

Title: A <div> with the class slider-title displays the page's title with the typewriter animation.

Testimonials: Each testimonial is placed inside a .swiper-slide with the testimonial text and author details. The author's avatar is displayed using an image tag with a round shape (avatar class).

Dependencies:
Swiper: The page uses the Swiper library for the carousel, linked via a CDN.

Custom Styling: The page uses internal CSS for styling, with a focus on responsiveness and interactivity.

Responsive Design:
The layout is responsive, with the Swiper slider adjusting based on the screen size (maximum width of 900px).

The body is set to flexbox, ensuring content is centered and adapts to the viewport height.

Overall Structure:
The page is designed to present testimonials in an interactive and visually engaging way, with smooth animations, a video background, and easy theme switching.

This code is ideal for a testimonials section or a personal portfolio where user feedback or reviews are displayed in a modern and stylish format. The use of Swiper enhances the interactivity of the page.
