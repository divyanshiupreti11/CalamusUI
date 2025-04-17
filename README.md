CalamusUI - A Modern CSS Framework



CalamusUI is a lightweight, responsive CSS framework designed to make web development easy. It provides a comprehensive set of utility classes, components, and a grid system to create beautiful, responsive layouts with ease.
 
 Project Structure



The project consists of the following files:
HTML 

index.html: The main demo file showcasing grid, utility classes, and components. 

CSS 

main.css: Imports all other CSS files and defines global styles.

 reset.css: Base style reset for consistency. 

variables.css: Style variables.

grid.css: Implements a responsive 12-column grid system with breakpoints. 

utilities.css: Includes utility classes for spacing, display, flex, etc.

 components.css: – interface elements.

 dark-mode.css: Theme switching



Features



 1. Responsive Grid System 12-column layout with support for breakpoints: sm, md, lg, xl, 2xl. Includes column widths, offsets, and no-gutter rows.



 2. Utility Classes Ready-to-use classes for: Display: block, flex, grid, hidden, etc. Spacing: m-4, p-2, mt-1, px-3, etc. 

Alignment: items-center, justify-between, text-center, etc. Colors: text-primary, bg-success, border-gray, etc. 

Typography: text-lg, font-bold, uppercase, etc. 

Positioning: absolute, relative, z-10, etc. 

Others: shadows, borders, radius, transitions, etc. 



3. Reusable Components 

Pre-styled and customizable: 

Buttons: btn, btn-primary, btn-outline-secondary 

Cards: card, card-header, card-body 

Badges: badge, badge-primary 

Alerts: alert, alert-success, alert-danger 

Forms: form-control, form-group, form-check 

Tables: table, table-striped, table-bordered 

Modals: modal, modal-header, modal-body 



4. Dark Mode Toggle dark mode with: data-theme="dark" on <html> or <body>. 



All components and utilities are adapted for dark backgrounds.



 Usage 



Include



 CSS html CopyEdit 

<link rel="stylesheet" href="main.css" /> 



html CopyEdit 



<div class="container"> 



<div class="row">

 <div class="col-md-6">

 <div class="card">

 <div class="card-body">

 <h3 class="card-title">Example Card</h3> 

<p>This is a simple card component.</p> 

<button class="btn btn-primary">Learn More</button>

 </div> 

</div> 

</div> 

</div>

</div>



 Enable Dark Mode



 HTML



 CopyEdit  



<html data-theme="dark"><!-- OR --><body data-theme="dark">
