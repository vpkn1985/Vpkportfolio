Smooth Scrolling Behavior:
Added scroll-behavior: smooth; to the body CSS to enable smooth scrolling for the entire page when navigating via anchor links or scrolling manually.
Fade-In Animation on Scroll:
Added opacity: 0; and transform: translateY(50px); to section elements initially.
Added a .in-view class with opacity: 1; and transform: translateY(0); to animate sections into view when scrolled to.
Included JavaScript to detect when sections are in the viewport and add the .in-view class.
Hover Animations:
Added transition properties and hover effects to header h1, header p, h2, ul li, .experience-item, .project-item, .skill-category, and footer for subtle scale, translate, and color changes.
JavaScript for Scroll Detection:
Implemented a script to check if sections are in the viewport and apply the animation class dynamically as the user scrolls.
This updated code provides a visually appealing website with smooth scroll animations, enhancing the user experience
