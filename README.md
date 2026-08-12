# React Phone Catalog

## Overview

Welcome to the **React Phone Catalog**, a responsive e-commerce application developed with React and TypeScript according to the provided Figma design, with a focus on usability, responsive layout, and modern web development practices.

The application includes a product catalog with Phones, Tablets, and Accessories, product details pages, a shopping cart, favorites, sorting, pagination, sliders, and convenient navigation between pages.

## Demo

You can view a live demo of the application [DEMO](https://inna-code10.github.io/phone-catalog-react/).

## Design

The project was implemented according to the Figma design:

[FIGMA DESIGN](https://www.figma.com/design/T5ttF21UnT6RRmCQQaZc6L/Phone-catalog--V2--Original?node-id=0-1&p=f&t=bSQZmPbRePs5LMmp-0)

## Key Features

**BannerSlider:** Interactive banner slider with automatic transitions.

**ProductsSlider:** Horizontal product sliders for featured product sections.

**Shop by Category:** Navigation links to Phones, Tablets, and Accessories.

**Product Catalog:** Product lists with sorting and pagination controls.

**Product Details:** Detailed product information with image selection, product characteristics, available options, and breadcrumbs for navigation.

**Shopping Cart Management:** Add and remove products, update product quantities, and automatically calculate the total price.

**Favorites Management:** Add and remove products from the favorites page.

**State Management:** React Context is used to manage shared application state such as cart and favorites.

**Loading States:** Loader is displayed while product data is being loaded.

**Error Handling:** NotFoundPage handles unknown URLs and unavailable product states.

**Responsive Design:** The application is adapted for desktop, tablet, and mobile screen sizes.

## Challenges

Developing the application involved several challenges, particularly around integrating multiple e-commerce features while maintaining a responsive and convenient user experience.

### Key Challenges

**Feature Integration:** Integrating sliders, category navigation, sorting, pagination, product details, favorites, and cart functionality required careful component organization.

**Responsive Design:** Ensuring that all components and page layouts work correctly across desktop, tablet, and mobile screen sizes required responsive SCSS styling and testing.

**State Management:** Managing shared state for shopping cart and favorites across multiple pages required a structured approach using React Context.

**Routing and Navigation:** Implementing navigation between the home page, categories, product details, favorites, cart, and error pages required proper routing configuration with React Router.

**Product Data Handling:** Loading and working with product information from local API files required consistent data structures and TypeScript types.

**Sorting and Pagination:** Implementing sorting and pagination made it possible to browse larger product collections more conveniently.

**Product Details:** Creating detailed product pages required working with multiple images, product specifications, available options, and related navigation.

**Error Handling:** Handling invalid routes and unavailable product states was important to prevent broken pages and provide a clear user experience.

**User Experience:** Interactive sliders, breadcrumbs, product cards, cart controls, and responsive navigation required attention to usability and consistency.

**Testing and Debugging:** The project was checked with linting and formatting tools to maintain consistent code quality and prevent common implementation issues.

These challenges were addressed through reusable React components, TypeScript types, React Context, responsive SCSS styles, and structured application architecture.

## Installation & Setup

To install the project and run it locally, follow these steps:

Clone the repository:

```bash id="u0k4or"
git clone https://github.com/Inna-code10/phone-catalog-react.git
```

Navigate to the project directory:

```bash id="f4ctgk"
cd phone-catalog-react
```

Install dependencies:

```bash id="bw58ll"
npm install
```

Start the local development server:

```bash id="m5v27m"
npm start
```

Build & deploy:

```bash id="jx7oar"
npm run build
npm run deploy
```

## Technologies Used

**React:** For building the user interface and reusable application components.

**TypeScript:** For type safety and a more reliable development experience.

**Vite:** For development and optimized project builds.

**CSS Modules:** For scoped and modular component styling.

**React Context:** For managing shared application state such as cart and favorites.

**Sass / SCSS:** For advanced and responsive styling.

**React Router:** For routing and navigation between application pages.

**classnames:** For conditional CSS class management.

**Cypress:** For application testing.

**ESLint:** For linting JavaScript and TypeScript code.

**Stylelint:** For checking and formatting SCSS styles.

**Prettier:** For consistent code formatting.

