# Background Color Changer

This project is a simple web application that changes the background color of the page when a button is clicked.

## Demo

https://github.com/user-attachments/assets/9468573e-6f07-4bb5-81aa-4282679bdb65


## How to Use

1.  **Clone or Download:** Clone this repository to your local machine or download the ZIP file.
2.  **Open `index.html`:** Open the `index.html` file in your web browser.
3.  **Click the Button:** Click the "Change Background Color" button to see the background color change to a random color.

## Files Included

*   `index.html`: The main HTML file containing the structure of the page and the button.
*   `style.css`: The CSS file that styles the appearance of the page and button.
*   `script.js`: The JavaScript file that contains the logic for changing the background color.

## Functionality

The JavaScript code does the following:

1.  **Adds an event listener:** It attaches a click event listener to the button with the ID "colorButton".
2.  **`myfunction()`:** When the button is clicked, the `myfunction()` is executed.
3.  **`getRandomColor()`:** `myfunction()` calls the `getRandomColor()` function to generate a random hexadecimal color code.
4.  **Changes background color:** It sets the `background-color` style of the `body` element to the generated random color.

## Customization

*   **Styling:** You can modify the `style.css` file to customize the appearance of the button, page, and overall styling.
*   **Color Palette:**  You can change the `getRandomColor()` function to use a predefined set of colors instead of generating completely random ones.
*   **Transition:** The `transition` property in the `body` CSS adds a smooth color transition. You can adjust the duration of the transition to your liking.
*   **Additional Elements:** Add more HTML elements to the `index.html` page and add relevant styling rules to `style.css` to enhance the project.

## Technologies Used

*   HTML
*   CSS
*   JavaScript

## Deployment

You can deploy this project to a web hosting platform like:

*   GitHub Pages (easiest for static websites)
*   Netlify
*   Vercel

## Contributing

Feel free to contribute to this project by opening issues or submitting pull requests.

## License

This project is open-source and available under the [Specify License, e.g., MIT License]. See the `LICENSE` file for more details.

## Author

[Your Name]
