# Challenge 3: Form Styling Challenge

## Challenge Description:

Your task is to style a simple HTML form to make it visually appealing and user-friendly using CSS. The form should include common form elements like text inputs, email input, a dropdown select, a textarea, and a submit button.

## Design Description:

- The form should be contained within a visually defined container (e.g., a bordered box or card).
- Form elements (labels, inputs, select, textarea, button) should be well-aligned and spaced for readability.
- Labels should be clearly associated with their input fields and positioned appropriately (e.g., above or to the left of inputs).
- Use visual cues to indicate focus state for input fields (e.g., change border color or add a subtle shadow on focus).
- Style the submit button to be prominent and interactive.
- Improve the overall visual appearance of a basic HTML form, making it look more modern and user-friendly.

**Form Elements to Include:**

- **Name Input:** Text input field for name.
- **Email Input:** Email input field for email address.
- **Subject Dropdown:** Select dropdown menu with at least 3-4 options for subject (e.g., "General Inquiry", "Product Support", "Feedback", "Sales").
- **Message Textarea:** Textarea for a message.
- **Submit Button:** Button to submit the form.

**Visual Style:**

- **Color Palette:** Use a light background color for the form container (e.g., white or light gray), a primary text color (e.g., dark gray or black), a subtle border color for form elements (e.g., light gray), and an accent color for the submit button (e.g., blue or green).
- **Font:** Use a readable sans-serif font for form labels and input text.
- **Spacing:** Pay attention to spacing between labels and inputs, between form elements, and around the form container. Use margins and padding effectively.

## Specific Requirements and Tasks:

1.  **HTML Structure (`index.html`):**

    - Create an HTML form structure using the `<form>` element.
    - Include the following form elements:
      - Text input for "Name" (`<input type="text">`)
      - Email input for "Email" (`<input type="email">`)
      - Dropdown select for "Subject" (`<select>`) with at least 3-4 `<option>` elements.
      - Textarea for "Message" (`<textarea>`)
      - Submit button (`<button type="submit">` or `<input type="submit">`)
    - Use appropriate `<label>` elements to associate labels with each input field. Ensure proper `for` and `id` attributes are used for accessibility.
    - Structure your HTML form semantically and ensure it is well-formed.

2.  **CSS Styling (`styles.css`):**

    - **Form Container:**
      - Style the `<form>` element or a container `<div>` around the form to create a visually distinct form area. Add a background color, border, rounded corners, and padding.
      - Control the width of the form and center it on the page or within its section if needed.
    - **Labels:**
      - Style `<label>` elements to be clearly visible and positioned appropriately relative to their input fields (e.g., above or to the left). Ensure good spacing between labels and inputs.
    - **Input Fields (Text, Email, Select, Textarea):**
      - Style `<input type="text">`, `<input type="email">`, `<select>`, and `<textarea>` elements to have consistent styling for borders, padding, font, and background color.
      - Add focus styles to input fields to provide visual feedback when an element is focused (e.g., change border color, add box-shadow on focus using `:focus` pseudo-class).
    - **Submit Button:**
      - Style the submit button (`<button type="submit">` or `<input type="submit">`) to be visually prominent. Use a distinct background color, text color, padding, border-radius, and a hover effect.
    - **Form Layout and Spacing:**
      - Use CSS to control the layout of form elements and labels. Ensure proper alignment and spacing between form elements to create a clean and organized form layout. You can use Flexbox or Grid for form layout if desired, or simpler CSS techniques like margins and display properties.

3.  **Code Quality:**
    - Write clean, well-indented, and commented HTML and CSS code.
    - Use meaningful class names and IDs in your CSS.
    - Ensure your code is free of syntax errors.
    - Pay attention to accessibility best practices in form design (e.g., proper label association).

## Assessment Criteria:

Your submission for the Form Styling Challenge will be assessed based on the following criteria:

- **HTML Structure (20%):**

  - Semantic HTML form structure (`<form>`, `<label>`, `<input>`, `<select>`, `<textarea>`, `<button>`).
  - Correct use of `<label>` elements and association with inputs using `for` and `id` attributes (accessibility).
  - Well-formed and valid HTML.

- **CSS Styling - Form Container and Layout (30%):**

  - Effective styling of the form container to create a visually defined form area.
  - Good form layout and alignment of labels and input fields.
  - Appropriate use of spacing (margins and padding) to create a clean form layout.

- **CSS Styling - Form Elements (30%):**

  - Consistent and visually appealing styling of text inputs, email input, select dropdown, and textarea.
  - Effective focus styles for input elements.
  - Prominent and interactive styling of the submit button with hover effect.
  - Clean and organized CSS code for form elements.

- **Visual Design and User Experience (10%):**

  - Overall visual appeal of the styled form.
  - User-friendliness and readability of the form.
  - Improved visual presentation compared to a default unstyled HTML form.

- **Code Quality (10%):**
  - Code readability, indentation, and comments (where appropriate).
  - Meaningful class names and IDs in CSS.
  - Absence of syntax errors in HTML and CSS.
  - Attention to basic form accessibility.

## Submission:

Commit your `index.html` and `styles.css` files to the `form-styling-challenge` folder in your repository.

---
