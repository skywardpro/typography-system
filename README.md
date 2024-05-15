# Typography System

This SCSS utility provides a structured way to manage and apply consistent typographic styles across your web projects using predefined font styles, weights, and responsive breakpoints.

## Features

- **Predefined Font Styles and Weights**:  Includes common typographic settings for **'font-style'** and **'font-weight'** CSS properties.
- **Responsive Breakpoints**: Supports multiple devices with predefined breakpoints.
- **Dynamic Style Application**: Utilizes SCSS maps and mixins for easy application and maintenance of typographic styles.

## Getting Started

### Prerequisites

Ensure you have a SCSS compiler installed. You can use [Sass](https://sass-lang.com/install), another compatible compiler, or an online tool like [SassMeister](https://www.sassmeister.com/) to compile the SCSS into CSS.

### Installation

Clone this repository or download the SCSS file directly into your project folder.

```git clone https://github.com/skywardpro/typography-system.git```

### Usage

**1. Import the `spacing-system.scss` file into your main stylesheet, or compile it into a CSS file and use that instead.**


**2. Apply the generated typographic classes in your HTML to manage typography. For example:**

```
<h1 class="typo--bold">
  Your headline here
</h1>
<p class="typo--regular">
  Your paragraph here.
</p>

```
_The typo--bold class applies bold styling to your headline, while typo--regular ensures standard text appearance for body text._


**3. Responsive classes are also generated and can be utilized like:**

```
<div class="typo--body typo--body-big__tablet typo--bold__tablet">
  Your content here.
</div>
```
_Font size and weight adapt automatically at the tablet breakpoint, enhancing readability across devices._


## Customization

To customize spacing values or breakpoints, modify the **$font-styles** and **$font-weights** maps in the `typography-system.scss` file. Use your preferred SCSS compiler or an online tool like SassMeister to experiment with and generate your custom CSS.

## Contributing

Contributions are welcome! Please open an issue to discuss your ideas or submit a pull request.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.