# Slice Selector Web Component

## Introduction

Dive into the Slice Selector, a fresh take on web form inputs. This experimental web component lets users make selections with a visual twist, resembling the segments of a pie chart. It's a subtle yet delightful departure from the usual checkboxes or radio buttons, designed to make user interfaces more interactive and visually stimulating.

![Slice Selector Screenshot](doc/screenshot.png)

## Features

- **Visual Feedback**: Visualize choices dynamically, with segments filling up as selections are made.
- **Customizable Look**: Style the selectors to match your site with simple CSS.
- **Built for Accessibility**: Full keyboard navigation and ARIA attributes ensure it's usable for everyone.

## How It Works

The `slice-selector-group` contains individual `slice-selectors`. As users interact with the selectors, their states change, visually represented by the "filling" of each slice. This component is not just another form input; it's a conversation starter and an experience enhancer.

Integrating the Slice Selector into your project is a surefire way to elevate the user experience with a fun, interactive touch.

## Usage Example

```html
<slice-selector-group required="3">
  <slice-selector id="option1">Option 1</slice-selector>
  <slice-selector id="option2">Option 2</slice-selector>
  <slice-selector id="option3">Option 3</slice-selector>
  <slice-selector id="option4">Option 4</slice-selector>
  <slice-selector id="option5">Option 5</slice-selector>
</slice-selector-group>
```

Incorporate the Slice Selector into your project for a user-friendly, visually
engaging selection process.
