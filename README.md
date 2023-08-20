# Appending Text to `<p>` Tags

This simple web application allows you to input text into a textbox and append it to `<p>` tags with the click of an "Add" button. The added text will be displayed in the order they are added, with each new text appearing in a new `<p>` tag.

## Table of Contents

- [Introduction](#introduction)
- [Demo](#demo)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [JavaScript Functionality](#javascript-functionality)
- [License](#license)

## Introduction

The purpose of this project is to showcase how you can use JavaScript and DOM manipulation to dynamically add and display text in `<p>` tags on a web page.

## Demo

You can see a live demo of the project [here](https://22pankajsahu.github.io/m6Day9HomeWorkChallenge/).

## Usage

1. Clone or download this repository to your local machine.

2. Open the `index.html` file in a web browser.

3. You'll see an input textbox and an "Add" button.

4. Enter text into the textbox and click the "Add" button. The entered text will be appended to a new `<p>` tag within the output container.

5. Repeat step 4 to add more text. The new text will be added below the previously added text.

## Technologies Used

- HTML: The structure of the web page.
- CSS: Styling for the input elements.
- JavaScript: DOM manipulation for adding text to `<p>` tags.

## JavaScript Functionality

The JavaScript code included in the `script tag`  provides the functionality to add the entered text to `<p>` tags when the "Add" button is clicked. Here's how it works:

1. The button and input elements are selected from the DOM.

2. An event listener is added to the "Add" button to listen for clicks.

3. When the button is clicked, the input text is trimmed to remove leading and trailing spaces.

4. If the trimmed text is not empty, a new `<p>` element is created, and the entered text is set as its content.

5. The new `<p>` element is appended to the output container, and the input textbox is cleared.

This allows users to add multiple lines of text, each in its own `<p>` tag.

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to customize and expand this README.md to include additional details, such as troubleshooting tips, acknowledgments, or contributions. Make sure to replace "link-to-live-demo" with the actual link to your live demo if you decide to host the project online.

<br> <div align="center"> 

---
## Author

My name is PANKAJ SAHU i am the owner of this repository. It is My geekster's m6 Day9 HomeWork Challenge Project.

If you have any questions, suggestions, or feedback, you can reach out to the project maintainer:

 Name : [PANKAJ SAHU](https://linkedin.com/in/22pankajsahu-) <br>
 Email: [22pankajsahu@gmail.com](mailto:22pankajsahu@gmail.com)

<br>

---
</div>
