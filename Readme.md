 Happy Travel - Creation of a Landing Page

**Happy Travel** is a virtual travel agency with green and golden colors that make you dream of adventures. As I was learning HTML and CSS, I put a lot of effort into using new tags and properties like `flex`, `grid`, and `position`. Here, I’ll tell you what I did, how I did it, and how to test my project.

## What is Happy Travel?

Happy Travel is a website to explore destinations like Bali or Paris, search for your next trip, and learn about insurance for worry-free travel. It has a menu, a large search bar, a mosaic with destination photos, an insurance section, and a footer with social media. I also created an error page with a fun GIF for when something isn’t ready. I chose green colors to feel natural, golden tones for elegance, and the `'Times New Roman'` font because it seemed perfect for the style.

![imag](https://res.cloudinary.com/din119ww9/image/upload/v1747768354/Captura1_bc9aiz.png)

## What Did I Do?

Here’s what I accomplished:

1. **Main Page (`index.html` and `styles.css`)**:
   - I started with `<html>`, `<head>`, and `<body>`, and used tags like `<header>`, `<div>`, `<h1>`, `<h2>`, `<p>`, and `<a>` to build the page.
   - I created a menu with links to "Destinations," "Recommended Trips," and more, using `<nav>` and `<ul>`.
   - I added a search bar with text that says, "What’s your next destination?" and an image on the right.
   - In CSS, I used `background-color`, `rgba` for transparency, and `border-radius` to give everything rounded corners.

2. **Created a Destination Mosaic**:
   - I made a section with 6 destination photos, each with a name (like "Paris") and a "More Info" button.
   - I used `display: grid` to arrange the photos in 3 columns.
   - I gave it a different background to stand out against the green of the rest.
   ![imag2](https://res.cloudinary.com/din119ww9/image/upload/v1747768354/Captura2_ywaw6x.png)

3. **Made the Search Bar Stand Out**:
   - I wanted the search bar to be large and placed below the text "What’s your next destination?" with the image on the right.
   - I used `position: absolute` to place the text and search bar on the left, and `margin-left` for the image.
   - With `padding` and `font-size`, I made the search bar larger.

4. **Styled Everything with CSS**:
   - I organized `styles.css` starting with the menu and ending with the footer.
   - I learned to use `display: flex` to center things, `transition` for smooth button color changes, and `box-shadow` to add depth.

5. **Created an Error Page**:
   - I made `error_page.html` that says, "Oops, we’re building this website!" with a funny GIF of someone building.
   - I used `display: flex` to center the title, message, GIF, and a button to return to the homepage.
   - I learned to use `min-height` to make the page fill the screen and `backdrop-filter` for a blurry effect on the menu.

## Files I Created

- **`index.html`**: The main page with the menu, search bar, destination mosaic, insurance, and footer.
- **`styles.css`**: The styles for the main page, where I applied everything I learned about CSS.
- **`error_page.html`**: A page for when something isn’t ready.
- **`error_page.css`**: The styles for the error page, with the same green and golden colors.
- **`README.md`**: This file, where I explain my project.

## How to Use My Project

1. **What You Need**:
   - A browser like Chrome or Firefox.
   - Internet to load the images and GIF.

2. **How to Test It**:
   - Put all the files in a folder.
   - Open `index.html` in the browser to see the main page.
   - Open `error_page.html` to see the error page.
   - Check if the menu, photos, search bar, and GIF look good.

## What I Learned

- **HTML**: How to use `<div>`, `<h1>`, `<h2>`, `<a>`, `<img>`, and `<nav>` to build a page.
- **CSS**: Awesome properties like:
  - `display: flex` and `display: grid` to organize elements.
  - `position: absolute` and `margin` to move things.
  - `border-radius` for smooth corners.
  - `transition` for hover effects.
- **Colors**: How to use `rgba` for transparent colors and combine greens, golds, and coral.
- **Design**: That colors and design can make a page feel like an adventure.

## Things I Want to Improve

- Learn JavaScript to make the search bar actually search.
- Create more pages, like one for each destination.

## Notes

- The green and golden colors make the page feel like a trip, and the beige adds a special touch.
- I learned a lot playing with CSS, although I sometimes got confused with `position`.
**Thanks for checking out my school project! I hope you like it!** 🌴