# API Documentation Page

## Overview
A clean, responsive, and interactive API documentation webpage that provides detailed information about API endpoints, request/response formats, and error codes. The documentation supports both dark and light themes and offers various customization options for improved user experience.

## Features

### 🎨 Theme Support
- Dark mode (default) and light mode
- Theme preference saved in browser's local storage

### 📱 Responsive Design
- Adapts to different screen sizes (desktop, tablet, mobile)
- Adjustable content density (compact, comfortable, spacious)

### 🔧 Customization Options
- Font size adjustment (small, medium, large)
- Layout density control
- Optional code copying functionality
- Collapsible response examples

### 🧩 Interactive Elements
- Copy-to-clipboard buttons for code examples
- Collapsible sections for API responses
- Settings menu for customization
- Syntax highlighting for code blocks

### 📚 Content Organization
- Clearly structured endpoint documentation
- Detailed parameter and response field explanations
- HTTP status code reference
- Authentication information

## How to Use

1. **Open the HTML file** in any modern web browser.

2. **Navigate through sections** using the structured layout:
   - Introduction and base URL
   - Health Check Endpoints
   - Service Handler Endpoints
   - Response Fields Explanation
   - Error Codes

3. **Customize your experience** by clicking the settings icon in the top-right corner:
   - Toggle between dark and light themes
   - Adjust font size
   - Change layout density
   - Toggle copy buttons visibility
   - Enable/disable auto-expanded examples

4. **Interact with endpoints** by:
   - Reading endpoint descriptions
   - Viewing example requests
   - Examining response structures
   - Testing API calls using the provided curl commands

## Technical Details

- Built with pure HTML, CSS, and JavaScript (no frameworks)
- Uses CSS variables for theming
- Stores user preferences in localStorage
- Responsive design using media queries
- Semantic HTML structure

## Customization

You can easily customize this documentation by:

1. Modifying the CSS variables in the `:root` selector to change colors
2. Adding new endpoints by copying and modifying the existing endpoint HTML structure
3. Updating the content within each section to match your API specifications
4. Extending the JavaScript functionality to add more interactive features

## Browser Compatibility

This documentation page works in all modern browsers including:
- Chrome (and Chromium-based browsers)
- Firefox
- Safari
- Edge

## License

Feel free to use and modify this documentation template for your own projects.

---

Built with ❤️ for API developers and users
