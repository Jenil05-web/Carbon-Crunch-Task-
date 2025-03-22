I have used Technologies like -  HTML , CSS and Javascript to add styling and make a responsive webpage.
Approach of the project:
Created a fixed-position navigation bar at the top using <nav>
Responsive Basics: Uses vh (viewport height) and % for flexibility.

Hover Effects: Buttons lift up slightly on hover.

Color Theme: Green (#2e8b57) for environmental vibe.
Uses flexbox to space elements evenly

position: fixed ensures it stays visible during scrolling

Z-index (z-index: 1000) guarantees it overlays other content
A clean, professional landing page focused on environmental sustainability services with clear hierarchy and intuitive navigation. The design emphasizes action through contrasting CTA buttons while maintaining visual harmony with nature-themed styling.

viewport meta tag for mobile scaling.

Relative units (%, rem) for flexibility
Mobile-first sizing (padding: 0 20px for side spacing)

Flexbox for centering content vertically/horizontally

i have added scroll triggered animations using javascript 
it will trigger when 20% of element is visible
it require css matching classses .
 used window.scrollY to detect vertical scroll position.
 Used  native scrollIntoView with smooth behavior

Missing block property (should add block: 'start' for better control)