 # Add Friend Feature

This code implements a simple "Add Friend" feature for a social media platform. It consists of an HTML file, a CSS file, and a JavaScript file.

## HTML File

The HTML file defines the structure of the web page. It includes a `<div>` element with the id "card" that contains an image, a heading, a subheading, and a button.

### Overview:
This project demonstrates the creation of a visually appealing product card using HTML and CSS. The card features an image, a heading, a subheading, and two buttons. The goal is to provide a detailed explanation of the code, allowing a junior developer to understand and implement the design.

- We start by creating a basic HTML structure with a `<!DOCTYPE html>` declaration, `<html>`, `<head>`, and `<body>` tags.
- Inside the `<head>` section, we include a `<title>` tag for the page title and a `<link>` tag to reference the external CSS file (`style.css`).
- The `<body>` section contains a `<div>` element with an `id` of `"card"`. This `div` will serve as the container for our product card.
- Inside the `#card` `div`, we include an `<img>` tag for the product image, an `<h1>` tag for the product name, an `<h5>` tag for the product price, and two `<button>` tags for the "Buy Now" and "Add to Cart" actions.

### Friend or Stranger

This code snippet demonstrates a simple JavaScript program that allows a user to toggle between the status of "Friend" and "Stranger" by clicking a button. The code uses the `querySelector` method to select the HTML elements with the IDs `istatus` and `add`. The `istatus` element is a heading (h5) that displays the current status, while the `add` element is a button that triggers the status change.

The program uses a variable called `check` to keep track of the current status. Initially, `check` is set to 0, indicating that the status is "Stranger". When the user clicks the button, the program checks the value of `check`. If `check` is 0, it means the current status is "Stranger", so the program updates the `istatus` element to display "Friends", changes the color of the text to green, and changes the button text to "Remove Friend". It also sets `check` to 1 to indicate that the new status is "Friend".

If `check` is 1, it means the current status is "Friend", so the program updates the `istatus` element to display "Stranger", changes the color of the text to red, and changes the button text to "Add Friend". It also sets `check` to 0 to indicate that the new status is "Stranger".
