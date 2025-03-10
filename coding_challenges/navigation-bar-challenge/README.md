# Challenge 1: Navigation Bar Challenge

## Challenge Description:

Your task is to create a responsive navigation bar for a website using HTML and CSS. The navigation bar should be horizontally oriented and contain links to different sections of a website. It should adapt its layout for both desktop and mobile views.

## Design Description:

**Desktop View:**

- The navigation bar should be positioned at the top of the page.
- Navigation links should be displayed horizontally in a row.
- Links should be evenly spaced across the navigation bar.
- Use a visually distinct background color for the navigation bar.
- On hover, navigation links should change color or style to indicate interactivity.

**Mobile View (Screen width less than 768px):**

- The navigation bar should collapse into a "hamburger menu" icon on the right side.
- Clicking the hamburger menu icon should expand a vertical menu below the navigation bar, displaying the navigation links in a column.
- The expanded vertical menu should overlay the main content or push the content down.
- The hamburger menu icon should change appearance (e.g., to a close "X" icon) when the menu is expanded.

**Visual Style:**

- **Color Palette:** Use a primary background color for the navigation bar (e.g., `#f0f0f0` or a light gray), a contrasting text color for links (e.g., `#333` or dark gray), and an accent color for hover effects (e.g., a shade of blue or green).
- **Font:** Use a clean, sans-serif font for the navigation links (e.g., Arial, Helvetica, sans-serif).
- **Responsiveness:** Ensure the navigation bar transitions smoothly between desktop and mobile views.

## Specific Requirements and Tasks:

1.  **HTML Structure (`index.html`):**

    - Create an HTML structure for the navigation bar using semantic HTML5 elements (e.g., `<header>`, `<nav>`, `<ul>`, `<li>`, `<a>`).
    - Include at least 4-5 navigation links (e.g., "Home", "Products", "Services", "About", "Contact").
    - For the mobile view, include a "hamburger menu" icon (you can use a simple icon using CSS or an actual icon image/font icon). Initially, this icon should be visible only in mobile view.
    - Ensure your HTML is well-formed and uses proper semantic tags.

2.  **CSS Styling (`styles.css`):**

    - **Desktop Navigation Bar:**
      - Style the `<nav>` element to create the horizontal navigation bar with a background color and padding.
      - Use Flexbox or Grid to layout the navigation links horizontally and space them evenly.
      - Style the navigation links (`<a>` elements) for text color, remove underlines, and add hover effects (e.g., change color, background, or add an underline).
    - **Mobile Hamburger Menu:**
      - Initially, hide the navigation links (`<ul>` list) in mobile view using CSS (e.g., `display: none;`).
      - Style the "hamburger menu" icon (create it using CSS or use an icon image/font icon). Make it visible in mobile view and hidden in desktop view using media queries.
      - Use JavaScript (or pure CSS if you are comfortable with checkbox/radio button hacks, though JavaScript is recommended for clarity) to toggle the visibility of the vertical navigation menu when the hamburger icon is clicked.
      - Style the expanded vertical navigation menu (when the hamburger icon is clicked) to display the links in a column below the navigation bar. Style the links in the vertical menu.
    - **Responsiveness:**
      - Use CSS media queries to adjust the layout and appearance of the navigation bar for screen widths below 768px (or your chosen breakpoint for mobile view).
      - Ensure the transition between desktop and mobile views is smooth and functional.

3.  **Code Quality:**
    - Write clean, well-indented, and commented HTML and CSS code.
    - Use meaningful class names and IDs in your CSS.
    - Ensure your code is free of syntax errors.

## Assessment Criteria:

Your submission for the Navigation Bar Challenge will be assessed based on the following criteria:

- **HTML Structure (25%):**

  - Semantic HTML5 is used correctly (`<header>`, `<nav>`, `<ul>`, `<li>`, `<a>`).
  - Well-formed and valid HTML.
  - Logical structure for navigation elements and hamburger menu icon.

- **CSS Styling - Desktop Navigation (30%):**

  - Effective styling of the horizontal navigation bar layout using Flexbox or Grid.
  - Visually appealing styling of navigation links (colors, hover effects, no underlines).
  - Clean and organized CSS code for desktop navigation.

- **CSS Styling - Mobile Hamburger Menu (30%):**

  - Effective implementation of the hamburger menu icon and its visibility control using media queries.
  - Functionality of the hamburger menu to toggle the vertical navigation menu (using JavaScript or CSS).
  - Styling of the expanded vertical navigation menu and its links.
  - Clean and organized CSS code for mobile navigation.

- **Responsiveness (10%):**

  - Navigation bar correctly adapts to different screen sizes (desktop and mobile).
  - Smooth transition between desktop and mobile layouts using media queries.

- **Code Quality (5%):**
  - Code readability, indentation, and comments (where appropriate).
  - Meaningful class names and IDs in CSS.
  - Absence of syntax errors in HTML and CSS.

## Submission:

Commit your `index.html` and `styles.css` files (and any images if used) to the `navigation-bar-challenge` folder in your repository.

---


