# 3weekbootstrap

Migrating previous work to implement bootstrap

# Migrating a Site to Bootstrap

## Challenge

Bootstrap is not only a great tool for scaffolding websites quickly, but its utility classes and pre-made components make it an excellent choice for maintaining and updating existing sites. For this reason, developers often migrate existing sites to Bootstrap to simplify updates and continued support.

In this challenge, you will take one of your existing projects (either from Week 1 or Week 2) and migrate it to Bootstrap. The final project should be deployed using GitHub Pages, so it is accessible online. You've also learnt about jQuery Widgets, so feel free to use any Widgets that you feel might enhance your site further

## Key Learnings

By completing this exercise, you will:

- Gain practical experience in using Bootstrap within a website.
- Learn how to incorporate Bootstrap's responsive grid system, components, and utility classes into an existing project.
- Understand the benefits of using a front-end framework like Bootstrap for easier maintenance and scalability.
- Practice deploying a site using GitHub Pages.
- (optional) Gain experience of installing and using jQuery Widgets

## User Story

As a developer, I want to migrate my existing website to Bootstrap so that I can leverage its responsive design, utility classes, and pre-built components for easier updates and maintenance.

## Acceptance Criteria

- Take an existing site from Week 1 or Week 2 and migrate it to use Bootstrap for layout, styling, and components.
- Incorporate Bootstrap's responsive grid system to ensure the site is mobile-friendly.
- Use at least **three Bootstrap components** (e.g., Navbar, Cards, Buttons, Forms) to replace existing UI elements.
- Utilize **Bootstrap utility classes** (e.g., spacing, text alignment, background colors) to simplify styling.
- Ensure the migrated site looks clean, responsive, and functions correctly across various screen sizes.
- If using jQuery Widgets, ensure they are installed and working correctly
- Deploy the migrated site using GitHub Pages, ensuring it is publicly accessible.

## Getting Started

1. **Choose an existing site:**
   - Select one of your previous projects from Week 1 or Week 2 that you will be migrating to Bootstrap.

2. **Add Bootstrap to your project:**
   - Include Bootstrap's CSS and JavaScript in your HTML file by adding the following lines inside the `<head>` section:
     ```html
     <link
       href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css"
       rel="stylesheet"
     />
     <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
     ```
3. **Migrate the layout to Bootstrap:**
   - Use Bootstrap's [Grid System](https://getbootstrap.com/docs/4.5/layout/grid/) to restructure your layout for responsiveness. For example:
     ```html
     <div class="container">
       <div class="row">
         <div class="col-md-6">
           <!-- Your content here -->
         </div>
         <div class="col-md-6">
           <!-- Your content here -->
         </div>
       </div>
     </div>
     ```

4. **Incorporate Bootstrap components:**
   - Replace existing UI elements with Bootstrap components. For example, replace a navigation menu with the [Navbar component](https://getbootstrap.com/docs/4.5/components/navbar/):
     ```html
     <nav class="navbar navbar-expand-lg navbar-light bg-light">
       <a class="navbar-brand" href="#">Navbar</a>
       <div class="collapse navbar-collapse">
         <ul class="navbar-nav mr-auto">
           <li class="nav-item">
             <a class="nav-link" href="#">Home</a>
           </li>
           <li class="nav-item">
             <a class="nav-link" href="#">About</a>
           </li>
         </ul>
       </div>
     </nav>
     ```

5. **Use Bootstrap utility classes:**
   - Simplify your CSS by replacing custom styles with Bootstrap's utility classes (e.g., `.text-center`, `.mt-4`, `.bg-primary`).

6. **Test responsiveness:**
   - Ensure that your site is responsive and works well on different screen sizes.

7. **Deploy the site on GitHub Pages:**
   - Push your migrated project to GitHub and [deploy it on GitHub Pages](https://pages.github.com/).

## Example

Here’s an example of how you might convert a simple header and layout into Bootstrap:

```html
<header class="bg-primary text-white text-center p-3">
  <h1>My Bootstrap Website</h1>
</header>

<div class="container mt-4">
  <div class="row">
    <div class="col-md-8">
      <p>This is the main content area.</p>
    </div>
    <div class="col-md-4">
      <p>This is the sidebar.</p>
    </div>
  </div>
</div>
```

## Submission

Once your site has been migrated and deployed, submit the link to your GitHub Repo and GitHub Pages deployment.

## Additional Resources

- [Bootstrap Documentation](https://getbootstrap.com/docs/4.5/getting-started/introduction/)
- [Bootstrap Components](https://getbootstrap.com/docs/4.5/components/alerts/)
- [Bootstrap Utility Classes](https://getbootstrap.com/docs/4.5/utilities/spacing/)
- [GitHub Pages: Getting Started](https://docs.github.com/en/pages/getting-started-with-github-pages)
- [jQuery UI Widgets Documentation](https://api.jqueryui.com/category/widgets/)
- [jQuery UI Demos and Code Samples](https://jqueryui.com/)

# Grading Rubric: Migrating a Site to Bootstrap

---

### **Technical Implementation – 30%**

Evaluates the extent to which Bootstrap is properly integrated and utilized:

- Migrates an existing project to use **Bootstrap 4.5** for layout and styling.
- Implements **Bootstrap’s grid system** to restructure layout for responsiveness.
- Incorporates **at least three Bootstrap components** (e.g., Navbar, Cards, Buttons, Forms).
- Uses **Bootstrap utility classes** (e.g., spacing, text alignment, colors) to reduce custom CSS.
- Optional: Integrates **jQuery Widgets**, ensuring correct installation and functionality.

---

### **Styling & Bootstrap Integration – 20%**

Assesses styling quality and Bootstrap usage:

- Demonstrates clear understanding of Bootstrap's utility-first approach.
- Avoids unnecessary custom styles in favor of Bootstrap classes.
- Applies a consistent color scheme and spacing using Bootstrap's utility classes.
- Ensures all replaced components match or improve upon original design.

---

### **Responsiveness & Device Compatibility – 20%**

Checks for effective responsive design:

- Site is **fully responsive** on mobile, tablet, and desktop screens.
- Grid system adapts layout correctly across screen sizes.
- Navigation and UI elements remain accessible and usable on all devices.
- Avoids layout-breaking issues or elements that overflow the screen.

---

### **Code Quality & Accessibility – 10%**

Measures maintainability and accessibility practices:

- Code is clean, well-organized, and free of major errors.
- Semantic HTML tags are preserved during migration.
- Accessibility attributes are used appropriately (`alt`, `aria`, `label for`, etc.).
- Code avoids duplication and follows DRY principles.

---

### **Deployment – 10%**

Evaluates whether the site is live and accessible:

- Project is successfully deployed via **GitHub Pages**.
- Live URL is provided and loads correctly.
- All styles, scripts, and assets function without errors or missing files.

---

### **Repository Quality – 5%**

Reviews project structure and version control:

- Clear and descriptive repository name.
- Logical folder/file structure.
- Git commit history is frequent, with meaningful messages.
- `README.md` includes project description, GitHub Pages link, and basic setup info.

---

### **Visual Design & UX – 5%**

Assesses user interface and design polish:

- Layout is visually clean and easy to navigate.
- Bootstrap components are used consistently and enhance the site's aesthetics.
- Text is readable; spacing and alignment are thoughtfully applied.
- Interaction feedback (hover states, button effects) is implemented smoothly.

---

## ✅ Total: 100%
