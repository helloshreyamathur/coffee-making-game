# Coffee Making Game - AI Agent Instructions

## Project Overview
This is a minimalist web-based coffee brewing simulation game focusing on precision and craftsmanship. The project uses vanilla HTML, CSS, and follows a Braun-inspired design aesthetic.

## Architecture & Structure
- `index.html`: Entry point containing the main game structure and content
- `styles.css`: Global styles using CSS variables and modern layout techniques
- Design system is based on the following components:
  ```css
  :root {
    --primary-color: #1a1a1a;    // Main text and UI elements
    --background-color: #f5f5f5; // Page background
    --accent-color: #ff5733;     // Highlights and interactive elements
  }
  ```

## Design Patterns & Conventions
# Coffee Making Game - AI Agent Instructions

## Project Overview
This is a minimalist web-based coffee brewing simulation game focusing on precision and craftsmanship. The project uses vanilla HTML, CSS, and follows a Braun-inspired design aesthetic.

## Architecture & Structure
- `index.html`: Entry point containing the main game structure and content
- `styles.css`: Global styles using CSS variables and modern layout techniques
- Design system is based on the following components:
  ```css
  :root {
    --primary-color: #1a1a1a;    /* Main text and UI elements */
    --background-color: #f5f5f5; /* Page background */
    --accent-color: #ff5733;     /* Highlights and interactive elements */
  }
  ```

## Design Patterns & Conventions
1. **Typography**:
   - Uses Inter font family (400 & 600 weights)
   - Main headings: 3rem, letter-spacing: -0.03em
   - Body text: 1.1rem with 1.8 line height

2. **Layout**:
   - Centered single-column design
   - Container max-width: 600px
   - Content max-width: 480px for readability
   - Consistent vertical rhythm using rem units

3. **Component Structure**:
   - Container → Content → Elements hierarchy
   - Uses semantic HTML5 elements (main, h1, p)
   - Dividers used for visual separation

## Development Guidelines
1. **CSS Organization**:
   - Follow existing CSS variable naming pattern
   - Group related properties
   - Use relative units (rem) for spacing and typography
   - Maintain existing class naming convention

2. **HTML Structure**:
   - Maintain semantic markup
   - Follow established nesting pattern
   - Keep accessibility in mind with proper ARIA attributes

## Important Notes
- The project is in early development with focus on UI/UX
- Design system is modular and should be extended using existing patterns
- Future game mechanics should maintain the minimalist aesthetic