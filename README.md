# Modern CSS Reset

A lightweight, forward-thinking CSS reset that provides a clean foundation for modern web projects. This reset addresses common browser inconsistencies while implementing best practices for accessibility, typography, and responsive design.

## Features

- **Intuitive Box Model**: Uses `box-sizing: border-box` for more predictable layouts
- **Modern Typography**: Implements `text-wrap: pretty` for paragraphs and `text-wrap: balance` for headings
- **Responsive Media**: Ensures images and media are properly contained and responsive
- **Form Normalization**: Standardizes form elements across browsers
- **Accessibility First**: Includes reduced-motion support and improved focus handling
- **Modern CSS Support**: Enables view transitions and animation control
- **Performance Optimized**: Improves text rendering and layout stability

## Usage

### Basic Installation

1. Copy the CSS into your project:
2. Add it to your HTML:
    
    ```html
    <link rel="stylesheet" href="path/to/reset.css">
    ```

    Or import it in your main CSS file:
    
    ```css
    @import 'path/to/reset.css';
    ```

## Browser Support

This reset uses modern CSS features like dynamic viewport units (dvh), improved text wrapping (text-wrap: pretty and text-wrap: balance), and view transitions. It follows progressive enhancement principles, meaning core functionality works in all browsers while newer features gracefully enhance the experience in modern browsers. Older browsers will receive a solid, functional foundation, while users of up-to-date browsers will benefit from improved typography, animations, and layout stability. This approach ensures your site remains accessible to all users while still taking advantage of the latest web platform capabilities.

## Why Use This Reset?

### Compared to Traditional Resets

Unlike traditional CSS resets that strip all styling, this modern reset:

- Preserves useful defaults
- Enhances typography and readability
- Improves accessibility
- Supports modern CSS features
- Provides a solid foundation without overriding too much

## Customization

Feel free to modify this reset for your specific needs. You might want to:

- Add your own typography preferences
- Adjust form styling
- Customize focus states
- Modify animation behavior

## License

MIT License - feel free to use in personal and commercial projects.