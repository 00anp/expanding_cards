# Expanding Cards Interaction

## Description
A responsive webpage that features expanding image panels. Clicking on any panel expands it, revealing a title, and minimizing the others. The design is fully responsive with media queries to handle smaller screen sizes, ensuring an optimal user experience across devices.

## Features
- Interactive and animated image panels that expand on click.
- Smooth transitions between the panels for a visually appealing experience.
- Mobile-friendly design with adjustments for smaller screens.
  
## Tech Stack
- **HTML5**: Structure and layout of the webpage.
- **CSS3**: Styling and transitions, including flexbox for layout and media queries for responsiveness.
- **JavaScript**: Interactivity, handling click events to expand the selected panel.

## Setup Instructions
1. Clone the repository:
    ```bash
    git clone <repository-url>
    ```
2. Navigate to the project directory:
    ```bash
    cd expanding-cards
    ```
3. Open `index.html` in your browser:
    ```bash
    open index.html
    ```

## Code Explanation
- **HTML**: The page contains a container `<div>` with five child `div` elements, each representing an image panel. The panels have a background image and a `<h3>` title.
  
- **CSS**: 
  - Flexbox is used to align and distribute the panels within the container.
  - The panels expand on click by changing their `flex` property and using CSS transitions for a smooth effect.
  - Media queries hide two of the panels when the screen width is below 480px to ensure responsiveness.

- **JavaScript**: 
  - Each panel has an event listener for the click event. When clicked, the panel becomes active by adding an `active` class, and the rest of the panels shrink.
  - The `removeActiveClasses` function ensures that only one panel is active at a time.

## Screenshots
Include some screenshots of the project here to give a visual overview (Optional).

## License
This project is licensed under the MIT License - see the LICENSE file for details.

