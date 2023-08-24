# animations
hosted link https://ajit7568.github.io/animations/

![Screenshot (84)](https://github.com/ajit7568/animations/assets/104454960/84cf2573-8087-4ee2-b326-b333b34ff418)
![Screenshot (85)](https://github.com/ajit7568/animations/assets/104454960/f2d9869e-4d8c-44dd-b7b3-f8d9d1604fc3)
![Screenshot (86)](https://github.com/ajit7568/animations/assets/104454960/a3ea627e-61d3-4f45-a07f-b792311735fa)
![Screenshot (87)](https://github.com/ajit7568/animations/assets/104454960/2760a106-7f59-4ea0-8ef7-9bad7ea893bb)

 HTML code creates a webpage with a container displaying three images that have interactive hover effects and slight animations. Let's break down the code step by step:

<!DOCTYPE html>: This declares that the document is written in HTML5.

<html lang="en">: The opening tag for the HTML document, indicating the language of the content.

<head>: This section contains meta information and the document's title. It also includes an embedded <style> block for adding CSS directly to the document.

<meta charset="UTF-8">: Specifies the character encoding as UTF-8.
<meta http-equiv="X-UA-Compatible" content="IE=edge">: Sets the compatibility mode for Internet Explorer.
<meta name="viewport" content="width=device-width, initial-scale=1.0">: Configures the viewport for responsiveness.
<title>Document</title>: Sets the title of the webpage.
<style>: This is an embedded CSS block that contains styles for the page's appearance.

*: This selector applies the following styles to all elements on the page.

margin: 0; padding: 0; box-sizing: border-box;: Resets margins and padding and sets box sizing to border-box.

body: Styles for the <body> element:

display: flex; justify-content: center; align-items: center;: Centers content both horizontally and vertically.
background-color: #000;: Sets the background color to black.
min-height: 100vh;: Ensures a minimum height of the viewport's height.
.container: Styles for the container <div> element:

display: flex; width: 1100;: Displays the container as a flexbox with space between the elements.
-webkit-box-reflect: below 1px linear-gradient(transparent,transparent,#0004);: Adds a slight reflection effect below the container.
.container img: Styles for the images within the container:

max-width: 350px;: Limits the maximum width of the images.
transform-origin: center; transform: perspective(800px) rotateY(20deg);: Applies a 3D perspective and rotation to the images.
transition: 0.5s;: Adds a smooth transition effect over 0.5 seconds.
box-shadow: 0px 0px 8px grey;: Adds a subtle shadow to the images.
border-radius: 5px;: Rounds the corners of the images.
.container:hover img: Styles for the images within the container when the container is hovered:

opacity: 0.3;: Reduces the opacity of the images to create a fade-out effect on hover.
.container img:hover: Styles for the images themselves when hovered:

transform: perspective(800px) rotateY(0deg);: Resets the rotation on hover.
opacity: 1;: Sets the opacity to full, making the image fully visible.
<body>: The main content of the webpage.

<div class="container">: A container <div> that holds the images.
Three <img> elements with src attributes pointing to image files.
Each <img> element has an alt attribute providing alternative text for the images.
This code creates an engaging webpage where the images rotate and change opacity with hover interactions, giving a dynamic and visually appealing effec
