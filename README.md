# Microsoft Logo README

## Overview

This HTML and CSS template represent a stylish Microsoft logo with colorful squares. The design uses a grid layout to arrange four colored squares, each representing a different Microsoft brand color. The Microsoft logo text is displayed below the squares with a bold and shadowed style.

## Usage

To view the Microsoft logo, simply open the [Microsoft Logo Webpage](https://dipakavaidya.github.io/MicrosoftLogo/MicrosoftLogo/) in your web browser.

## HTML Structure

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Microsoft</title>
   <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="box">
        <span class="square red"></span>
        <span class="square green"></span>
        <span class="square blue"></span>
        <span class="square yellow"></span>
    </div>
    <div class="para">
        <p>MicroSoft</p>
    </div>
</body>
</html>
```

## CSS Styles

```css
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    background-color: #232323;
}

.box {
    position: relative;
    display: grid;
    grid-template-columns: 130px 130px;
    grid-column-gap: 12px;
    grid-row-gap: 12px;
    grid-row: auto auto;
    filter: drop-shadow(0px 0px 40px #858585);
}

.para {
    position: absolute;
    top: 75%;
}

p {
    color: #fff;
    font-size: 42px;
    font-weight: bold;
    letter-spacing: 3px;
    filter: drop-shadow(13px 13px 6px #000);
}

.square {
    width: 130px;
    height: 130px;
}

.red {
    background-color: #f65314;
}

.green {
    background-color: #7cbb00;
}

.blue {
    background-color: #00a1f1;
}

.yellow {
    background-color: #ffbb00;
}
```

## Styling Details

- **Background**: The body has a dark background color (#232323).
- **Logo Squares**: The logo consists of four colored squares arranged in a 2x2 grid.
- **Microsoft Text**: The "MicroSoft" text is styled with a bold font, white color, and a shadow effect.
- **Square Colors**: Each square represents a different Microsoft brand color - red, green, blue, and yellow.

Feel free to explore and customize the code to create your own variations.

## Author

This logo template was created by Dipak  A Vaidya.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

