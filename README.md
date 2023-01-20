# Joon.K-Bio

FCC certification project2

- The project is to create a tribute page.
- I decided to do a little bio about myself.
- This simple project consists of adding images, paragraphs, ul, etc.
- my personal goal is to properly utilize the @media query to create a responsive page with proper ratios and layouts based on the screen size.

- Having trouble adding image from local hard-drive.
- Not sure if it's even possible.
- Problem solved by using relative path rather than a full path.

- Still need to work on CSS, the real challenge

## Add link to use google font

```<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=[font_name]">```

- When using multiple font names, it should be separated by a '|'.
- If the font name has a space in it, use a '+' ('font+name') when adding font name to the link element
- If the font name has a space in it, use single quotes 'font name' when applying to CSS.

## Styling image file using CSS

- Use an img-container div and margin: auto method to center the image.

``` .img-container {
      width: 100%;
      text-align: center; /* This will also center the image horizontally*/
}

    img {
        margin: auto; /* center the image horizontally and vertically*/
        width: 100%;
        max-width: 800px;
        max-height: 600px;
        object-fit: cover; /* Ensure that the image fills the entire container while maintaining aspect ratio*/
    }

- Still need to learn how to properly use properties for margin: auto, flex-box method, as well as the 'position' property.

## social media icon alignment issue

- 'codepen' icon font seems to have a different width compared to other icons such as 'github', 'twitter', and 'linked-in'.
- Trying to use flex box to apply 'space-between', 'space-around', but it does not seem to work. 