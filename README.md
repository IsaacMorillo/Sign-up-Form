# Sign-up Form

A small front-end practice for creating a registration interface with a classical mythology theme and a two-column layout.

The page combines semantic HTML, custom CSS, and a visual approach inspired by the aesthetic of the gods of Olympus, with a modern registration form and native browser validation.

## Overview

This project is a user registration page that shows a visual section on the left with a background illustration and a heading that provides context for the experience, while the right side contains the registration form.

The main goal is to practice form layout, style organization, and building functional interfaces using pure HTML and CSS.

## Features

- Two-column layout design
- Visual header with background image and highlighted text
- Registration form with fields for:
  - first name
  - last name
  - email
  - phone
  - password
  - password confirmation
- HTML5 validation such as:
  - `required`
  - `minlength`
  - `pattern`
  - `type="email"`
  - `type="tel"`
- Visual style with a custom font based on a thematic typeface
- Focus and invalid-state styles to provide visual feedback to the user
- CSS reset to standardize browser behavior

## Project structure

```text
Sign-up-Form/
├── README.md
├── index.html
├── reset.css
├── styles.css
├── fonts/
│   ├── Norse.otf
│   └── Norsebold.otf
├── img/
│   └── mythologyart-ai-generated-8546415_1920.png
└── (possible additional script not included in this repository)
```

## Main files

### `index.html`

This file defines the main structure of the page. The layout includes:

- a left-side panel with the background image and welcome text
- a right-side area with registration information
- a form with several fields that simulate account creation
- links for "Log in" and references to the original image on Pixabay

The document uses the title `Sign-up for Olympus` and presents the concept of "entering Olympus and living among the gods" as the thematic narrative.

### `styles.css`

This file centralizes the visual appearance of the project:

- loads the custom `Norse` typography
- defines the base layout using `display: flex`
- configures the width of the left and right panels
- sets the header background with the local image
- customizes text, buttons, fields, and form elements
- adds styles for focus and invalid validation states

### `reset.css`

This is a reusable CSS reset for normalizing cross-browser styling. Among other things, it:

- adjusts `box-sizing`
- removes default margins
- improves how images and media elements are rendered
- preserves font inheritance in inputs, buttons, and selects
- improves `line-height` and text smoothing behavior

## Technologies used

- HTML5
- CSS3
- CSS reset
- Local font files (`.otf`)
- Basic responsive design with a front-end practice focus

## Notes

This project is a UI and layout practice exercise, not a functional application with a backend. The forms are prepared to be extended with additional validation or integration in the future.

The structure is light, clear, and easy to understand, making it ideal for learning concepts such as:

- web page design
- semantic structure of forms
- CSS for layout and aesthetics
- basic validation with HTML
- management of local assets and images

## License

This repository does not currently include an explicit license file. If you plan to reuse or share it, review the repository settings or add an appropriate license based on your needs.

## Author

Project developed by Isaac Morillo.


