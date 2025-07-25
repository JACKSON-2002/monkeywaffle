BOOTSTRAP CLASSES EXPLANATION FOR CAFE.HTML
==============================================

This document explains all the Bootstrap classes used in the cafe.html file, organized by category:

🎨 LAYOUT & GRID SYSTEM CLASSES
================================

Container Classes:
- container: Responsive fixed-width container
- container-fluid: Full-width container spanning entire viewport

Grid System:
- row: Creates horizontal groups of columns
- col-lg-6: 6 columns wide on large screens (≥992px)
- col-lg-4: 4 columns wide on large screens
- col-md-6: 6 columns wide on medium screens (≥768px)
- col-md-4: 4 columns wide on medium screens
- col-md-2: 2 columns wide on medium screens
- col-4: 4 columns wide on all screens
- col-6: 6 columns wide on all screens

🧭 NAVIGATION CLASSES
=====================

Navbar Components:
- navbar: Base navbar class
- navbar-expand-lg: Navbar expands on large screens
- navbar-dark: Dark navbar theme
- navbar-brand: Brand/logo styling
- navbar-toggler: Mobile menu toggle button
- navbar-toggler-icon: Hamburger icon for mobile menu
- navbar-nav: Navigation list container
- nav-item: Individual navigation item
- nav-link: Navigation link styling
- collapse: Collapsible content
- navbar-collapse: Collapsible navbar content

🎯 POSITIONING & DISPLAY CLASSES
=================================

Position:
- fixed-top: Fixed positioning at top of viewport
- position-relative: Relative positioning

Alignment:
- align-items-center: Centers items vertically in flexbox
- justify-content-center: Centers items horizontally
- text-center: Centers text alignment
- text-md-end: Right-aligns text on medium+ screens

Display:
- d-flex: Applies flexbox display
- visually-hidden: Hides content visually but keeps it for screen readers

📐 SPACING CLASSES
==================

Margin Classes:
- m-1: Margin of 0.25rem on all sides
- mb-4: Margin bottom of 1.5rem
- mb-5: Margin bottom of 3rem
- me-2: Margin end (right) of 0.5rem
- me-3: Margin end of 1rem
- ms-auto: Auto margin start (pushes to right)
- ms-4: Margin start of 1.5rem
- mt-2: Margin top of 0.5rem
- mt-4: Margin top of 1.5rem
- my-3: Margin top and bottom of 1rem

Padding Classes:
- p-4: Padding of 1.5rem on all sides
- px-4: Padding left and right of 1.5rem
- py-4: Padding top and bottom of 1.5rem
- py-5: Padding top and bottom of 3rem

🎨 BACKGROUND & COLOR CLASSES
=============================

Background Colors:
- bg-dark: Dark background color
- bg-light: Light gray background color

Text Colors:
- text-white: White text color
- text-danger: Red text color (for menu sections)
- text-warning: Yellow/orange text color
- text-success: Green text color
- text-info: Blue text color
- text-muted: Muted gray text color
- text-dark: Dark text color

🔲 BORDER CLASSES
=================
- border: Adds default border
- border-0: Removes border
- border-dark: Dark border color
- border-warning: Yellow/orange border color
- border-primary: Blue border color

📦 COMPONENT CLASSES
====================

Card Components:
- card: Bootstrap card component
- card-body: Card content area
- card-title: Card title styling
- card-text: Card text content

Modal Components:
- modal: Modal dialog container
- modal-fade: Fade animation for modal
- modal-dialog: Modal dialog wrapper
- modal-dialog-centered: Centers modal vertically
- modal-content: Modal content container
- modal-header: Modal header section
- modal-body: Modal body section

Button Classes:
- btn: Base button class
- btn-warning: Yellow/orange button
- btn-success: Green button
- btn-outline-light: Outlined light button
- btn-outline-secondary: Outlined gray button
- btn-lg: Large button size
- btn-close: Modal close button

Form Classes:
- form-control: Styled form input

Carousel Classes:
- carousel: Carousel container
- carousel-slide: Sliding carousel
- carousel-inner: Inner carousel wrapper
- carousel-item: Individual carousel slide
- carousel-control-prev: Previous button
- carousel-control-next: Next button
- carousel-control-prev-icon: Previous arrow icon
- carousel-control-next-icon: Next arrow icon

📱 RESPONSIVE & UTILITY CLASSES
===============================

Responsive Heights:
- min-vh-100: Minimum viewport height of 100%
- h-100: Height 100% of parent

Spacing Utilities:
- gap-3: Gap of 1rem between flex items

Font Classes:
- fw-bold: Bold font weight
- display-3: Large display heading (3)
- display-4: Large display heading (4)
- display-5: Large display heading (5)
- display-6: Large display heading (6)
- lead: Emphasized paragraph text

Shadow Classes:
- shadow-sm: Small box shadow

🎭 SEMANTIC & ACCESSIBILITY CLASSES
===================================

Screen Reader Classes:
- visually-hidden: Content hidden visually but available to screen readers

Role Attributes (HTML5 + Bootstrap):
- role="navigation": ARIA navigation role
- role="banner": ARIA banner role
- role="contentinfo": ARIA footer role

🔧 DATA ATTRIBUTES FOR JAVASCRIPT
==================================

Bootstrap JavaScript:
- data-bs-toggle="collapse": Bootstrap collapse toggle
- data-bs-target="#navbarNav": Target element for toggle
- data-bs-dismiss="modal": Dismiss modal action
- data-bs-ride="carousel": Auto-start carousel
- data-bs-interval="3000": Carousel interval timing
- data-bs-slide="prev": Previous slide action
- data-bs-slide="next": Next slide action

ARIA Accessibility:
- aria-label: Accessible label
- aria-hidden="true": Hide decorative elements from screen readers
- aria-expanded="false": Expandable element state
- aria-controls: Element being controlled
- aria-labelledby: References label element

📊 SUMMARY BY CATEGORY
======================

- 🎨 Layout: 15+ grid and container classes
- 🧭 Navigation: 10+ navbar classes  
- 📐 Spacing: 20+ margin/padding utilities
- 🎨 Colors: 10+ background/text color classes
- 📦 Components: 25+ card, modal, button, carousel classes
- 📱 Responsive: 10+ responsive and utility classes
- ♿ Accessibility: 8+ ARIA and screen reader classes

This comprehensive use of Bootstrap classes creates a fully responsive, accessible, and professional-looking Belgian waffle website with minimal custom CSS required!

CUSTOM CLASSES USED (defined in styles.css)
===========================================

Menu-specific classes:
- menu-category: Custom menu category container
- category-title: Menu category heading style
- category-subtitle: Menu category subtitle
- section-title: Menu section titles
- subsection-title: Menu subsection titles
- menu-item: Individual menu item container
- item-name: Menu item name styling
- item-price: Menu item price styling
- star: Star rating styling
- new-badge: "New" badge for menu items
- veg-icon: Vegetarian indicator icon
- hero-section: Custom hero section background
- hero-icon: Large animated waffle icon
- discount-popup: Custom popup modal styling
- coupon-section: Coupon code section
- coupon-input: Coupon input field
- partner-logo: Delivery partner logo container
- delivery-partner: Delivery partner item
- extra-goodness: Special menu section styling
- extras-grid: Grid layout for extras
- extra-item: Individual extra item
- combo-description: Combo description styling
- combo-item: Combo menu item
- contact-card: Contact information cards
- stat-item: Statistics display items
- social-links: Social media links container

These custom classes work together with Bootstrap to create the authentic Belgian Waffle Co. design and functionality.
