# README

## Overview

This project is a Vue.js-based web application designed to be integrated into a Squarespace website. It provides an interactive interface for users to input various statistical parameters and receive calculated results, specifically focusing on sample size estimations with and without Bonferroni adjustments.

## Features

- **Responsive Design**: Utilizes Bootstrap for a responsive layout, ensuring usability across different devices and screen sizes.
- **Interactive Input Fields**: Custom Vue.js components for input fields with real-time formatting and validation.
- **Dynamic Output**: Displays calculated results based on user inputs, with support for Bonferroni-adjusted and non-adjusted sample sizes.
- **Tooltips**: Font Awesome icons and Bootstrap tooltips for enhanced user guidance.

## Dependencies

- **Font Awesome**: For icons.
- **Bootstrap 5.3.3**: For responsive design and UI components.
- **Vue.js**: For the reactive user interface.
- **Numeral.js**: For number formatting.

## Installation

1. **Add HTML**: Integrate the provided HTML code into your Squarespace page.
2. **Include Dependencies**: Ensure that the external dependencies (Font Awesome, Bootstrap, Vue.js, Numeral.js) are included in your Squarespace site's header or page settings.

## Usage

1. **Input Fields**: Fill in the required statistical parameters, such as Confidence Level, Power, Minimum Detectable Effect (MDE), etc.
2. **Calculate**: The app will automatically calculate and display the required sample sizes and estimated duration based on the provided inputs.
3. **Tooltips**: Hover over the question mark icons to get more information about each field.

## Code Structure

- **HTML Structure**: The HTML code sets up the layout, input fields, and output areas.
- **CSS Styles**: Custom styles are included within the `<style>` tag to manage the layout and responsiveness.
- **Vue.js Application**: The Vue.js application handles the logic for data input, formatting, calculations, and dynamic updates of the UI.
