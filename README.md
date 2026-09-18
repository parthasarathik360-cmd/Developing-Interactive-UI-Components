# Week 2 Task: Interactive UI Components

## Accessible

This project is an interactive FAQ Accordion developed using HTML5, CSS3, and Vanilla JavaScript. The objective is to demonstrate how a reusable and maintainable front-end component can improve user experience through clear interaction, responsive design, accessibility, keyboard support, and smooth visual transitions.

## Project Overview

The FAQ Accordion allows users to expand and collapse frequently asked questions. When a question is selected, its corresponding answer becomes visible while other open questions are automatically closed.

The component has been designed without external JavaScript libraries or frameworks so that the implementation clearly demonstrates DOM manipulation, event handling, CSS styling, and JavaScript logic.

## Technologies Used

* HTML5
* CSS3
* Vanilla JavaScript
* ARIA accessibility attributes
* Responsive CSS
* CSS transitions

## Features

* Interactive expand/collapse functionality
* Single-open-item accordion behavior
* Responsive design for desktop, tablet, and mobile
* Keyboard navigation
* ARIA attributes for accessibility
* Focus-visible keyboard styling
* Smooth opening and closing transitions
* Reduced-motion support
* Defensive JavaScript error handling
* CSS fallback for browsers without CSS Grid support
* Semantic HTML structure
* Reusable JavaScript initialization function

## Project Structure

```text
week-2-interactive-ui/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

### index.html

Contains the semantic structure of the FAQ component, including buttons, questions, answers, and accessibility attributes.

### style.css

Contains the visual design, responsive layout, accordion states, animations, focus styles, and browser fallbacks.

### script.js

Handles DOM manipulation, click events, keyboard navigation, accordion state management, ARIA updates, and error handling.

## How to Run

No server or installation is required.

1. Download or extract the project folder.
2. Open the project folder.
3. Double-click `index.html`.
4. The FAQ Accordion will open in your default browser.

The project can also be tested using a local development server such as the Live Server extension in Visual Studio Code.

## How to Use

Click any FAQ question to display its answer.

Click the same question again to close it.

Opening another question automatically closes the previously opened question.

These features make the component easier to use with keyboards and assistive technologies.

## Responsive Design

The component is designed to work across different screen sizes.

Responsive CSS media queries adjust:

* Page spacing
* Font sizes
* Button spacing
* Icon sizes
* Answer content spacing

The component can be tested on:

* Desktop computers
* Laptops
* Tablets
* Mobile phones

## Error Handling

The JavaScript includes defensive checks to prevent errors when expected DOM elements are missing.

For example, if the accordion container or FAQ buttons cannot be found, the script displays a warning in the browser console instead of causing the entire application to fail.

## Future Improvements

Possible future improvements include:

* Search functionality for FAQs
* Multiple accordion groups
* Dynamic FAQ loading from JSON
* Category filtering
* Dark mode
* Persisting the selected FAQ using localStorage
* Adding animated icons
* Integrating the component into a larger website

## Conclusion

This project demonstrates the development of an interactive and reusable front-end UI component using standard web technologies. It focuses on DOM manipulation, event handling, accessibility, responsive design, maintainable JavaScript, error handling, and browser compatibility.

The component can be reused in websites such as product pages, documentation sites, support portals, portfolios, and service websites.
