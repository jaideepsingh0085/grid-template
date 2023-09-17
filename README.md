# grid-template
![Screenshot 2023-09-17 231717](https://github.com/jaideepsingh0085/grid-template/assets/128147644/a1bfe376-7dbd-461e-8339-ff8c36273571)
![Screenshot 2023-09-17 231916](https://github.com/jaideepsingh0085/grid-template/assets/128147644/4a212b0a-7e62-4b4c-b577-81bea575805d)
![Screenshot 2023-09-17 231926](https://github.com/jaideepsingh0085/grid-template/assets/128147644/cc89701d-e320-49e7-aaa0-f4ce03379372)
![Screenshot 2023-09-17 231939](https://github.com/jaideepsingh0085/grid-template/assets/128147644/f5e159de-c2eb-464b-a94e-b3cd97a18848)
![Screenshot 2023-09-17 231945](https://github.com/jaideepsingh0085/grid-template/assets/128147644/77e28a44-b51a-4b9e-8e94-b9adc90e0a00)
![Screenshot 2023-09-17 231953](https://github.com/jaideepsingh0085/grid-template/assets/128147644/8589b2ff-3826-4667-87de-90bb69979f06)
![Screenshot 2023-09-17 231959](https://github.com/jaideepsingh0085/grid-template/assets/128147644/78a43dbe-66ae-409c-a237-b650b802df2d)
![Screenshot 2023-09-17 232009](https://github.com/jaideepsingh0085/grid-template/assets/128147644/3fca6d69-29a6-4bd5-b5e4-b50c0f85d2ad)

Hosted Link :https://jaideepsingh0085.github.io/grid-template/

HTML :
<!DOCTYPE html>: Declares the document type and version of HTML being used.
<html lang="en">: Defines the HTML document and specifies the language as English.
<head>: Contains metadata about the HTML document.
<meta charset="UTF-8">: Sets the character encoding to UTF-8 for proper text rendering.
<meta name="viewport" content="width=device-width, initial-scale=1.0">: Sets the viewport properties for responsive design.
<title>: Sets the title of the web page displayed in the browser tab.
<link rel="stylesheet" href="style.css">: Links an external CSS file called "style.css" for styling.
<body>: Contains the visible content of the web page.
<main class="main">: Defines the main content section of the page with a class attribute for styling.
<article class="t1 testimonial light">: Represents a testimonial section with specific classes for styling.
<div>: A generic container for grouping and styling elements.
<img src="..." alt="...">: Embeds an image with a source URL and alternate text for accessibility.
<h2>: Defines a level 2 heading.
<p>: Represents a paragraph of text.
</article>: Closes the testimonial article section.
</body>: Ends the body of the HTML document.
</html>: Closes the HTML document.

CSS :
*: Targets all elements and sets their box model, margin, padding, font, and font-weight properties.
box-sizing: Specifies the box model to include padding and border in element sizing.
margin: Sets the outer spacing around elements to zero.
padding: Sets the inner spacing within elements to zero.
font-family: Defines the preferred font family for text content.
font-weight: Specifies the thickness of characters in the font.
body: Styles the entire webpage's background, display, and alignment.
display: Sets the display mode of an element (grid in this case).
place-content: Centers content both horizontally and vertically within an element.
min-height: Specifies the minimum height of an element as a percentage of the viewport height.
background-color: Sets the background color of an element.
.main: Styles the main content container using grid layout, defining grid areas, width, gap, and padding.
grid-template-areas: Defines the layout of child elements within the grid container.
width: Sets the maximum width of the grid container.
gap: Specifies the gap between grid items.
grid-auto-columns: Sets the size of automatically generated grid columns.
padding-block: Sets the padding on the block axis (top and bottom).
margin-inline: Sets the margin on the inline axis (left and right).
.testimonial: Styles testimonial elements, including padding, border-radius, and box-shadow.
.t1, .t2, .t3, .t4, .t5: Styles specific testimonial elements with unique backgrounds.
.light, .dark: Styles text color for light and dark testimonial sections.
.desc-heading: Styles font size and margin for description headings.
.desc: Styles opacity, font size, line height, and margin for descriptions.
.name: Styles the container for names and images using flex layout and gap.
.name img: Styles images within name containers, applying border-radius and width.
.name h2: Styles heading font size within name containers.
.name p: Styles paragraph font size and opacity within name containers.
