# BaseConv — Number Base Converter

> An educational tool for converting numbers between different bases, with step-by-step explanations for every conversion.

-----

## What is BaseConv?

BaseConv is a single-file web application that converts numbers between the most common numeral systems — **binary, decimal, hexadecimal, and octal** — while showing a detailed, step-by-step breakdown of the process behind each conversion.

It was built not just to give you the result, but to help you **understand how and why** the conversion works. Ideal for students, developers, or anyone learning about number systems.

-----

## Features

- 8 conversion types supported
- Step-by-step explanation for every result
- Reference tables and verification steps included
- Example values to try with one click
- Light and dark theme toggle
- English and Turkish language support (EN / TR)
- Works as a PWA — installable on mobile home screen with its own icon
- No dependencies, no build step — pure HTML, CSS, and JavaScript

-----

## Supported Conversions

|From       |To         |
|-----------|-----------|
|Decimal    |Binary     |
|Decimal    |Hexadecimal|
|Decimal    |Octal      |
|Hexadecimal|Binary     |
|Hexadecimal|Decimal    |
|Binary     |Decimal    |
|Binary     |Hexadecimal|
|Octal      |Decimal    |

-----

## How to Use

1. **Choose a conversion type** from the grid at the top
1. **Enter your value** in the input field
1. Press **Convert** or hit `Enter`
1. Read the **step-by-step breakdown** below the result
1. Use the **Copy** button to copy the result to clipboard

You can also click any of the **example chips** below the input to quickly load a sample value.

-----

## Installing as a Mobile App (PWA)

BaseConv supports being added to your home screen as a Progressive Web App.

**On iOS (Safari):**

1. Open the file in Safari
1. Tap the Share button
1. Select “Add to Home Screen”
1. Confirm — the BaseConv icon will appear on your home screen

**On Android (Chrome):**

1. Open the file in Chrome
1. Tap the menu (⋮)
1. Select “Add to Home Screen”

-----

## Project Structure

```
baseconv/
└── index.html   # The entire application — HTML, CSS, and JS in one file
```

-----

## Customization

All styles are defined with CSS custom properties at the top of the file, making it easy to adjust colors, fonts, and spacing:

```css
[data-theme="dark"] {
  --accent: #c8a96e;   /* Main accent color */
  --bg: #0e0f11;       /* Background */
  --surface: #161719;  /* Card/surface color */
}
```

-----

## Browser Support

Works in all modern browsers (Chrome, Firefox, Safari, Edge). No polyfills needed.


-----

*Concept by [Tiago de Souza](https://github.com/tiag0-infosec)*
