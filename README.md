# Portfolio Project

Welcome to the **Portfolio Project** repository! This project is a fully responsive, modern portfolio website showcasing various sections such as header, about, portfolio, contact, and footer. The design and structure are optimized for all screen sizes using SCSS with media queries.

## Demo

![Project Demo](./img/demo.gif)

## Features

- **Responsive Design**: Optimized for desktop, tablet, and mobile devices using SCSS mixins and media queries.
- **Customizable Colors and Styles**: Centralized variables for consistent theming.
- **Reusable Mixins**: Flexbox-based layout utilities.
- **Modern Typography**: Google Fonts integration for a unique look.
- **Interactive Components**: Hover effects, active states, and animations for enhanced user experience.

## Technologies Used

- **HTML**: Semantic structure for web content.
- **SCSS**: Advanced styling with variables, mixins, and nesting.
- **Font Awesome**: Icon library for social media links and interactive elements.
- **Google Fonts**: Typography enhancement with the `Special Elite` font.

## Folder Structure

```
project-root/
|-- img/                # Image assets for the project
|-- styles/             # SCSS files for styling
|   |-- _variables.scss # Variables for colors and theming
|   |-- _mixins.scss    # Reusable mixins for layouts
|   |-- _media.scss     # Media query definitions
|   |-- main.scss       # Main SCSS file
|-- index.html          # Main HTML file
|-- README.md           # Project documentation
```

### Navbar

- Sticky navigation bar with a logo and menu.
- Menu items with hover and active states.

### Header

- Full-width background image with a title and button.
- Includes text with shadow effects for better visibility.

### About

- Section with text and an optional image.
- Buttons styled for interaction.

### Portfolio

- Grid layout for showcasing projects or works.
- Interactive hover effects for better presentation.

### Contact

- Form elements for collecting user input.
- Includes inputs, labels, and a textarea.

### Footer

- Includes logo, copyright text, and social media icons with hover effects.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/portfolio-project.git
   ```
2. Navigate to the project directory:
   ```bash
   cd portfolio-project
   ```
3. Open `index.html` in your browser to view the project.

## Customization

- Modify SCSS variables in `_variables.scss` to change colors and styles.
- Add your own images in the `img/` folder.
- Update content directly in `index.html`.

## Media Queries

The project is designed to adapt to the following breakpoints:

- **Extra Small (xsm)**: `0px - 575px`
- **Small (sm)**: `576px - 767px`
- **Medium (md)**: `768px - 1023px`

## Credits

- **Font Awesome**: [https://fontawesome.com](https://fontawesome.com)
- **Google Fonts**: [https://fonts.google.com](https://fonts.google.com)

## License

This project is open-source and available under the [MIT License](LICENSE).
