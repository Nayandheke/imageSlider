**Overview**
This project implements a visually appealing vertical card slider with interactive drag functionality. It allows users to navigate through a stack of cards by dragging their mouse vertically. The cards dynamically adjust their positions and sizes to create a smooth and engaging user experience.

**Features**
-Smooth vertical drag-to-slide functionality.
-Animated transitions for card positions, scales, and opacities.
-Customizable card styles with gradients and shadow effects using Tailwind CSS.
-Fully responsive design.

**Setup Instructions**
Prerequisites
-A modern web browser that supports ES6 JavaScript and CSS transitions.
-An internet connection to load TailwindCSS from the CDN.

**Steps**
1. Clone or Download the Project:Download the HTML file or copy the code provided above into a new file named index.html.
2. Run the Project:Open the index.html file in any modern browser. The application does not require any additional setup or dependencies.

**Technology Choices and Rationale**

1. HTML, CSS, and JavaScript
-These core technologies ensure the project is lightweight and compatible with any browser.

2. Tailwind CSS
-Simplifies styling with utility-first classes.
-Reduces the need for custom CSS, improving development speed and maintainability.

3. CSS Transitions
-Provides smooth animations for card scaling, positioning, and opacity changes.

4. JavaScript
-Handles user interactions, such as drag events and updating card styles dynamically.

**Known Limitations / Trade-Offs**
1. Mouse-Only Interaction
-The drag functionality is limited to mouse input. Touch support for mobile devices is not implemented.

2. Dependency on Tailwind CSS CDN
-The project relies on an external Tailwind CSS CDN. Offline usage would require downloading the Tailwind CSS library locally.

3. Threshold for Drag
-The card transition threshold (±150px) is hardcoded. This might not suit all devices and screen sizes.

4. Limited Customization
-Card styles and content are predefined in the HTML. Dynamic content generation is not supported.

**Future Improvements**

1. Add Touch Support
-Enhance the application to support touch gestures for mobile devices.

2. Dynamic Content
-Implement dynamic card generation using data fetched from an API or a backend service.

3. Accessibility Enhancements
-Include keyboard navigation and ARIA roles to improve accessibility.

4. Configurable Settings
-Allow users to adjust drag thresholds, transition speeds, and card styles through a settings panel.

5. Offline Support
-Bundle Tailwind CSS locally to enable offline usage.

**Acknowledgments**
-Tailwind CSS: For simplifying the styling process.
-Inspiration from modern web design patterns for card sliders.
