---
title: 'Light Theme Starter'
published: true
visible: true
---

! This theme is not maintained with the latest css variables. See [themes](https://wiki.kavitareader.com/en/guides/settings/themes) for all variables. 
```css
/* Theme for the light mode of Kavita */
:root .bg-light {
    --color-scheme: light;
    --primary-color: #4ac694;
    --primary-color-dark-shade: #3B9E76;
    --primary-color-darker-shade: #338A67;
    --primary-color-darkest-shade: #25624A;
    --error-color: #ff4136;
    --bs-body-bg: #fff;
    --body-text-color: #333;
    --btn-icon-filter: none;

    /* Navbar */
    --navbar-bg-color: black;
    --navbar-text-color: white;
    --navbar-fa-icon-color: white;
    --navbar-btn-hover-outline-color: rgba(255, 255, 255, 1);

    /* Inputs */
    --input-bg-color: #fff;
    --input-focused-border-color: #ccc;
    --input-bg-readonly-color: rgba(0,0,0,0.2);
    --input-placeholder-color: #aeaeae;
    --input-border-color: #ccc;
    --input-range-color: var(--primary-color);
    --input-range-active-color: var(--primary-color-darker-shade);

    /* Buttons */
    --btn-primary-text-color: black;
    --btn-primary-bg-color: white;
    --btn-primary-border-color: black;
    --btn-primary-hover-text-color: white;
    --btn-primary-hover-bg-color: black;
    --btn-primary-hover-border-color: black;
    --btn-alt-bg-color: #424c72;
    --btn-alt-border-color: #444f75;
    --btn-alt-hover-bg-color: #3b4466;
    --btn-alt-focus-bg-color: #343c59;
    --btn-alt-focus-boxshadow-color: rgb(68 79 117 / 50%);
    --btn-fa-icon-color: black;
    --btn-disabled-bg-color: #020202;
    --btn-disabled-text-color: white;
    --btn-disabled-border-color: #6c757d;

    /* Nav */
    --nav-link-active-text-color: white;
    --nav-link-bg-color: rgba(74, 198, 148, 0.9);
    --nav-tab-active-text-color: white;
    --nav-tab-text-color: var(--body-text-color);
    --nav-tab-bg-color: rgba(74, 198, 148, 0.9);
    --nav-tab-hover-border-color: #4ac694;
    --nav-link-text-color: black;
    --nav-link-hover-text-color: var(--primary-color);
    --nav-tab-border-hover-color: transparent;

    /* Side Nav */
    --side-nav-bg-color: rgba(255,255,255,0.6);
    --side-nav-mobile-bg-color: rgb(255,255,255);
    --side-nav-openclose-transition: 0.15s ease-in-out;
    --side-nav-box-shadow: none;
    --side-nav-mobile-box-shadow: 3px 0em 5px 10em rgb(0 0 0 / 50%);
    --side-nav-hover-text-color: white;
    --side-nav-hover-bg-color: black;
    --side-nav-color: black;
    --side-nav-border-radius: 5px;
    --side-nav-border: 1px solid rgba(0,0,0,0.2);
    --side-nav-border-closed: 1px solid transparent;
    --side-nav-companion-bar-transistion: 0.5s linear;
    --side-nav-border-transition: 0.5s ease-in-out;
    --side-nav-bg-color-transition: 0.5s ease-in-out;
    --side-nav-closed-bg-color: transparent;
    --side-nav-item-active-color: var(--primary-color);
    --side-nav-active-bg-color: rgba(0,0,0,0.5);
    --side-nav-item-active-text-color: white;
    --side-nav-overlay-color: rgba(0,0,0,0.5);


    /* Checkboxes */
    --checkbox-checked-bg-color: var(--primary-color);
    --checkbox-bg-color: white;
    --checkbox-border-color: var(--primary-color);
    --checkbox-focus-border-color: var(--input-border-color);

    /* Tagbadge */
    --tagbadge-bg-color: #c9c9c9;

    /* Toasts */
    --toast-success-bg-color: rgba(74, 198, 148, 0.9);
    --toast-error-bg-color: #BD362F;
    --toast-info-bg-color: #2F96B4;
    --toast-warning-bg-color: #F89406;

    /* Rating star */
    --ratingstar-star-empty: #b0c4de;
    --ratingstar-star-filled: var(--primary-color);

    /* Global */
    --accent-bg-color: rgba(206, 206, 206, 0.5); // Drawer had: var(--bs-body-bg)
    --accent-text-color: grey;
    --accent-text-size: 0.8rem;
    --hr-color: rgba(239, 239, 239, 0.125);
    --grid-breakpoints-xs: $grid-breakpoint-xs;
    --grid-breakpoints-sm: $grid-breakpoint-sm;
    --grid-breakpoints-md: $grid-breakpoint-md;
    --grid-breakpoints-lg: $grid-breakpoint-lg;
    --grid-breakpoints-xl: $grid-breakpoint-xl;
    --body-font-family: "EBGaramond", "Helvetica Neue", sans-serif;
    --brand-font-family: "Spartan", sans-serif;
    --text-muted-color: #aaa;

    /* Breadcrumb */
    --breadcrumb-bg-color: #eaeaea;
    --breadcrumb-item-text-color: var(--body-text-color);

    /* Card */
    --card-text-color: #000;
    --card-border-width: 0 1px 1px 1px;
    --card-border-style: solid;
    --card-border-color: #ccc;
    --card-progress-bar-color: var(--primary-color);
    --card-overlay-bg-color: rgba(0, 0, 0, 0);
    --card-overlay-hover-bg-color: rgba(0, 0, 0, 0.2);

    /* List items */
    --list-group-item-text-color: var(--body-text-color);
    --list-group-item-bg-color: white;
    --list-group-hover-text-color: var(--body-text-color);
    --list-group-hover-bg-color: #eaeaea;
    --list-group-item-border-color: rgba(239, 239, 239, 0.125);
    --list-group-active-border-color: none;

    /* Dropdown */
    --dropdown-item-hover-text-color: white;
    --dropdown-item-hover-bg-color: var(--primary-color);
    --dropdown-overlay-color: rgba(0,0,0,0.5);
    --dropdown-item-bg-color: white;

    /* Manga Reader */
    --manga-reader-overlay-filter: blur(10px);
    --manga-reader-overlay-bg-color: rgba(0,0,0,0.5);
    --manga-reader-overlay-text-color: white;
    --manga-reader-bg-color: black;
    --manga-reader-next-highlight-bg-color: rgba(65, 225, 100, 0.5);
    --manga-reader-prev-highlight-bg-color: rgba(65, 105, 225, 0.5);

    /* Radios */
    --radio-accent-color: var(--primary-color);
    --radio-hover-accent-color: var(--primary-color-dark-shade);

    /* Carousel */
    --carousel-header-text-color: black;
    --carousel-header-text-decoration: none;
    --carousel-hover-header-text-decoration: underline;

    /** Drawer */
    --drawer-background-color: white;
    --drawer-bg-color: white;
    --drawer-text-color: black;

    /* Pagination */
    --pagination-active-link-border-color: var(--primary-color);
    --pagination-active-link-bg-color: var(--primary-color);
    --pagination-active-link-text-color: white;
    --pagination-link-border-color: rgba(239, 239, 239, 1);
    --pagination-link-text-color: black;
    --pagination-link-bg-color: white;
    --pagination-focus-border-color: var(--primary-color);
    --pagination-link-hover-color: var(--primary-color);

    /** Event Widget */
    --event-widget-bg-color: white;
    --event-widget-item-bg-color: lightgrey;
    --event-widget-text-color: black;
    --event-widget-item-border-color: lightgrey;
    --event-widget-border-color: lightgrey;

    /* Popover */
    --popover-body-bg-color: var(--navbar-bg-color);
    --popover-body-text-color: var(--navbar-text-color);
    --popover-outerarrow-color: lightgrey;
    --popover-arrow-color: lightgrey;
    --popover-bg-color: lightgrey;
    --popover-border-color: lightgrey;

    /* Accordion */
    --accordion-header-text-color: rgba(74, 198, 148, 0.9);
    --accordion-header-bg-color: var(--bs-body-bg);
    --accordion-body-bg-color: var(--bs-body-bg);
    --accordion-active-body-bg-color: var(--bs-body-bg);
    --accordion-body-border-color: rgba(239, 239, 239, 0.125);
    --accordion-body-text-color: var(--body-text-color);
    --accordion-header-collapsed-text-color: var(--body-text-color);
    --accordion-header-collapsed-bg-color: var(--bs-body-bg);
    --accordion-button-focus-border-color: rgba(74, 198, 148, 0.9);
    --accordion-button-focus-box-shadow: unset;

    /* Search */
    --search-result-text-lite-color: rgba(0,0,0,1);

    /* Bulk Selection */
  --bulk-selection-text-color: var(--navbar-text-color);
  --bulk-selection-highlight-text-color: var(--primary-color);
  }

```