
# Frosted Glass Effect Card with Shape Overlay

This repository demonstrates a simple implementation of a frosted glass effect card with a shape overlay using HTML and CSS. The design is inspired by modern UI trends and can be used in various web applications, such as displaying masked information like on ATM cards.

## Features

- **Frosted Glass Effect**: The card uses the `backdrop-filter` property to create a frosted glass effect, making it look modern and sleek.
- **Shape Overlay**: A customizable shape overlay that covers specific content, useful for masking sensitive information.
- **Responsive Design**: The card is designed to be responsive, ensuring a consistent appearance across different screen sizes and devices.
- **3D Transformations Ready**: The design includes properties like `backface-visibility` for potential 3D transformations, such as a card flip effect.



### How It Works

- **Frosted Glass Effect**: This effect is achieved using the `backdrop-filter: blur(20px);` property, giving the card a blurred, translucent background.
- **Shape Overlay**: The `.sign i` element is positioned with a negative `right` value to overlay and partially cover content within the card.
- **Responsive Design**: The card's width and height are set to be responsive, adapting to the container's size.

## Usage

To use this design in your project:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/arjundipunath/atm-card.git
   ```

2. **Open the HTML File**:
   - Open the `index.html` file in your browser to view the frosted glass effect card.

3. **Customize**:
   - Modify the CSS in the `style.css` file to fit your design requirements. You can adjust the `border-radius`, `box-shadow`, and other properties.

## Contributing

Contributions are welcome! If you have ideas for improvements or new features, feel free to open an issue or submit a pull request.

---
