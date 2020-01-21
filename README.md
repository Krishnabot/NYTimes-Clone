# Positioning and Floating Elements

> This assignment consists of making a clone of a New York Times article page.

![Screenshot_2020-01-21 NYTimes Clone](https://user-images.githubusercontent.com/55361440/72814783-a5eb3f80-3c8b-11ea-9ce7-45eb257f26d9.png)

## Details  

### Nav Bar 
- The Nav bar have the NewYork Times headline (in center) ,and have two icons and two buttons(login and subscribe) on left and right respectively.(The nav-bar was created with the tag `<nav>` , and the buttons and icons have their sepreated `<div>` tags)

### Main Content Section

- The main content of the page (being the actual article and the right side sections) was made by creating some `<section>` tags only divided by the *Advertisement* spaces which are individual `<div>` tags.

- Since the main article container has already a *fixed* width and its container won't change even if the viewport does (because of it being at its minimal width already) the horizontal centering was achieved by using the `padding` property with an absolute value to its left and so allow the *aside* boxes to align using only the `float` property.

- The top bar icons were made using [Font Awesome](https://fontawesome.com/) and were contained and aligned with *flexboxes*

- As for each image, they were wrapped inside `<figure>` tags and took advantage of the `<figcaption>` elements to describe what was shown above.

### The `<aside>` tag and float

- One of the main requirement of this project is to create `<aside>` tag and use css property Float on it.

- Another `<section>` was created with the id #grid-boxes to create two coloums with 3 imgs in each of it.

- Right side content created  using the `<aside>` tag and used the property float:right on it.

### footer and footnotes 

- The `<footer>` tag was created for the content at the bottom. In this we have created multiple `<divs>` with multiple `<uls>` and `<lis>`

- Uses the New-york-Times logo as the heading of the `<footer>` and used The font awesome icons
at the right side for the very last `<li>s`.

## Built With

- HTML5, CSS3
- VSCode

## Live Demo

## Authors

👤 **Jaspreet Singh**
- Github: [@jaspreet-singh-sahota](https://github.com/jaspreet-singh-sahota)
- Twitter: [@jaspree88033250]https://twitter.com/jaspree88033250
- Linkedin: [jaspreet Singh]https://www.linkedin.com/in/jaspreet-singh-a28286146/

