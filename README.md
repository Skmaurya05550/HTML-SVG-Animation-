# HTML SVG Animation
## Demo
(https://ibb.co/GnzrbKC/)
 
This project is a simple HTML page showcasing an SVG animation of a logo badge and text, styled to mimic a dynamic outline drawing effect. The animation is triggered upon hovering over the SVG elements and brings the logo elements into full color and opacity with smooth transitions.

## Features

- **SVG-based logo** with animated outlines.
- Smooth **hover effect** on the logo and text elements.
- Customizable **stroke and fill animations** with a glowing effect on hover.
- **CSS keyframe animations** for the stroke dash offset and fill opacity transitions.

## How It Works

The animation leverages the `stroke-dasharray` and `stroke-dashoffset` properties of the SVG paths to create an outline drawing effect. When the page is loaded or hovered over, the stroke offset is animated, revealing the shape of the logo and text. The fill opacity is also animated to smoothly transition from 0 to 1, making the elements appear to fade in.

## CSS Animations

- **Stroke Animation**: The stroke gradually reveals the SVG paths by animating the `stroke-dashoffset` value.
- **Fill Animation**: The fill color fades in as the stroke is drawn.
- **Hover Effects**: The `hover` state changes the stroke and fill properties, adding a glowing effect to the SVG badge and text.

### Key CSS Rules:

- `@keyframes draw`: This controls the drawing effect of the logo paths by animating the `stroke-dashoffset` and `fill-opacity`.
- `@keyframes svg_outline`: Controls the fade-in of the logo and text after the outline animation is complete.

## Technologies Used

- **HTML5**
- **CSS3** (Keyframes, Transitions, Animations)
- **SVG** (Scalable Vector Graphics)

## File Structure

```bash
.
├── index.html       # Main HTML file
├── styles.css       # CSS for animations and styling
└── README.md        # Project documentation
