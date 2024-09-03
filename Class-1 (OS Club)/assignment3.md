

### **Assignment: Create a Responsive Navbar**

#### **Objective:**
The goal of this assignment is to design and implement a responsive navigation bar (navbar) using only HTML and CSS. The navbar should be functional and adjust its layout depending on the screen size (desktop, tablet, and mobile devices).

#### **Problem Statement:**
You are required to create a responsive navbar for a fictional website. The navbar should include the following elements:
1. **Logo**: Positioned on the left side of the navbar.
2. **Navigation Links**: A series of links (e.g., Home, About, Services, Contact) that should be displayed horizontally on larger screens.
3. **Hamburger Menu (for smaller screens)**: The navigation links should collapse into a hamburger menu on smaller screens (e.g., mobile devices). When the hamburger menu is clicked, it should expand to show the navigation links vertically.
4. **Responsive Design**: The navbar should look good and function correctly on various screen sizes, including desktops, tablets, and mobile phones.

#### **Requirements:**
1. **HTML Structure**:
   - Use semantic HTML elements where appropriate (e.g., `<nav>`, `<ul>`, `<li>`, `<a>`).
   - Include a logo on the left side of the navbar.
   - The navigation links should be inside an unordered list (`<ul>`).

2. **CSS Styling**:
   - Use Flexbox or CSS Grid to create a responsive layout.
   - Style the navbar to have a visually appealing design with appropriate colors, padding, and spacing.
   - Implement a media query to handle screen sizes below 768px:
     - The navigation links should collapse into a hamburger menu.
     - The hamburger menu should be visible only on smaller screens.
     - When the hamburger menu is clicked, the navigation links should be displayed vertically.
   - Ensure the navbar is fixed at the top of the page (optional but recommended).

3. **Responsiveness**:
   - Test the navbar on different screen sizes (desktop, tablet, mobile).
   - Ensure that the design is consistent and functional across all devices.

#### **Hints:**
- You can use the `display: none;` property to hide the navigation links initially on smaller screens and toggle it using the hamburger menu.
- Consider using CSS `:hover` and `:focus` pseudo-classes to add interactive effects.
- Use media queries to adjust the layout based on screen width.

#### **Bonus:**
- Add smooth scrolling when clicking on the navbar links (if the page contains sections corresponding to the links).
- Add a drop shadow or gradient to the navbar for a modern look.
- Include a hover effect on the navigation links.

