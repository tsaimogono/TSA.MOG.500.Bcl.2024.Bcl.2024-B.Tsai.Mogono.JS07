 [JSL06] Submission: CodeCuisine Menu Display System Challenge

You will:
1. Use the provided Starter Code Repository: https://github.com/CodeSpace-Academy/Module_6_StudentNo_Classcode_Group_Name-Surname_JSL06
2. Code your solution.
3. Commit changes to your GitHub repository.
4. Submit the GitHub Repository Link to the LMS [JSL06] Submission Project Tab.

In this coding challenge, you will build a simple menu display system for a fictional UberEats restaurant called "CodeCuisine." The goal is to display different categories of food items and allow users to add items to their order with a click. This challenge will help you apply various JavaScript concepts, including functions, closures, and event handling, to create an interactive menu.

![alt text](JSL06-solution.gif)

## Objectives:

- Create and use functions to dynamically populate the menu items on the page.
- Implement a callback function to handle adding items to the order.
- Use closures to maintain the state of the order.
- Utilize function expressions and anonymous functions.
- Call built-in functions and create custom functions to manage the menu and order system.

## Instructions:

1. **Setup Project Files**: Begin by creating three files: `index.html`, `index.css`, and `index.js`. Link your CSS and JS files to your HTML document.

2. **HTML Structure**: Build the HTML structure for your application. Include placeholders for the menu items and the order summary. Consider using `<div>` elements with appropriate IDs or classes for styling and scripting.

3. **Styling**: Use CSS to style your menu and order summary. Make the user interface visually appealing, and ensure that it's responsive and easy to navigate.

4. **JavaScript Implementation**: Use the provided starter code in `index.js` as a foundation for your application. The starter code contains placeholders for key functions and comments to guide you through the implementation.

    - `menu`: The `menu` object contains sample menu data, including categories and items. You can expand this menu with more items if needed.

    - `displayMenuItems(menu)`: This function should dynamically create and display menu items grouped by category. Iterate over the `menu` object and create HTML elements for each category and item. Attach event listeners to the menu items to handle adding items to the order.

    - `addToOrder(itemName)`: Implement this callback function to update the order summary when an item is added. You can use closures to maintain the state of the order. Calculate and update the total price accordingly.

    - `initMenuSystem(menu)`: Call the `displayMenuItems` function with the menu data and attach event listeners to menu items.

5. **Testing**: Thoroughly test your application to ensure that it correctly filters songs by genre for each Guardian and displays the playlists on the web page. Verify that you can add items to the order and that the order total updates as expected.

## What You Need to Do:

To complete this challenge, follow these steps:

1. Clone the provided Starter Code Repository to your local development environment: [Starter Code Repository](https://github.com/CodeSpace-Academy/Module_6_StudentNo_Classcode_Group_Name-Surname_JSL06).
2. Open the cloned project in your code editor.
3. Code your solution following the provided instructions and comments in the starter code.
4. Commit your changes to your local Git repository with meaningful commit messages.
5. Push your local Git repository to your GitHub account.
6. Verify that the changes have been successfully pushed to your GitHub repository.

## What You Need to Include:

1. Ensure that your code includes the necessary modifications to meet the challenge requirements.
2. Your GitHub repository should contain the updated code files.

## How We'll Assess Your Work:

1. We will review your GitHub repository to ensure that it contains the updated code files.
2. We will assess the modifications made to the code to verify that they effectively meet the challenge requirements.
3. We will consider the commit history and meaningful commit messages to evaluate your coding process.

By following these steps and completing the challenge, you will demonstrate your ability to create interactive web applications using JavaScript. Good luck, and enjoy building the CodeCuisine Menu Display System!

# Restaurant Menu Display

This project dynamically displays a restaurant menu with categories and items. Users can click on menu items to add them to an order, view the order list, and see the total price.

## Overview

The code defines a `menu` object containing categories of menu items (starters, main courses, desserts), a function to display the menu items dynamically on the webpage, and functions to add and remove items from the order list and update the total price accordingly.

## Usage

To use the menu system:

1. Open the `index.html` file in a web browser.
2. The menu items will be displayed by category.
3. Click on any menu item to add it to the order list.
4. The selected items will be listed in the order with the total price updated accordingly.
5. Click on an item in the order list to remove it.

## Features

- Dynamic display of menu items based on the provided menu object.
- Ability to add and remove items from the order list.
- Real-time calculation of the total price based on selected items.

## Challenges



1. **DOM Manipulation:** Manipulating the DOM to dynamically display menu items and update the order list and total price can be challenging, especially if you're new to JavaScript.

2. **Event Handling:** Handling click events on menu items and order items, and correctly updating the order and total price, requires a good understanding of event handling in JavaScript.

3. **Error Handling:** Implementing error handling to handle unexpected user input or invalid states can be complex, but it's essential for a smooth user experience.

5. **Testing:** Testing the functionality of the application, including edge cases and user interactions, can be time-consuming but is crucial to ensure the reliability of the system.
