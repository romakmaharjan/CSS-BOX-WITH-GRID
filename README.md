### HTML Code Explanation:
- <head>: Contains meta-information about the HTML document, such as character encoding, viewport settings, and external resources.
- <meta charset="UTF-8" />: Specifies the character encoding of the document as UTF-8, ensuring proper rendering of special characters.
- <meta http-equiv="X-UA-Compatible" content="IE=edge" />: Instructs Internet Explorer to use the latest rendering engine.
- <meta name="viewport" content="width=device-width, initial-scale=1.0" />: Sets the viewport width to the device width and initial scale to 1.0, ensuring proper responsiveness on various devices.
- <link rel="stylesheet" href="css/style.css" />: Links an external CSS file named "style.css" located in the "css" directory for styling the HTML content.
- <body>: Contains the visible content of the HTML document.
- <div class="container">: Defines a container for the content of the webpage.
- <h1 class="heading">our services</h1>: Displays a heading with the text "our services".
- <div class="box-container">: Contains a group of boxes representing different services.
- <div class="box">: Represents a box containing information about a specific service.
- <img src="image/icon-1.png" alt="" />: Displays an image representing the service, with the source "image/icon-1.png".
- <h3>HTML 5</h3>: Displays the name of the service as "HTML 5".
- <p>...</p>: Provides a brief description of the service.
- <a href="#" class="btn">read more</a>: Creates a link to read more about the service.
- The remaining <div class="box"> elements follow a similar structure, each representing a different service with its respective image, title, description, and "read more" link.

  ### Style CSS Code Explanation:
  - @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@100;200;300;400;500;600;700&display=swap');->  This line imports the Google Fonts stylesheet for the Poppins font family with various weights (100 to 700) and specifies to use the "swap" font-display strategy.
  - This block sets styles for all elements using the universal selector *.
- font-family: 'Poppins', sans-serif;: Sets the default font family to Poppins, and if not available, it falls back to a sans-serif font.
- margin: 0; padding: 0;: Removes default margin and padding from all elements.
- box-sizing: border-box;: Specifies the box-sizing model as border-box, where padding and border are included in the element's total width and height.
- outline: none; border: none;: Removes outline and border from all elements.
- text-decoration: none;: Removes text decoration (e.g., underlines) from all elements.
- text-transform: capitalize;: Sets the text transformation to capitalize, making the first letter of each word capitalized.
- transition: .2s linear;: Sets a transition effect with a duration of 0.2 seconds and linear timing function for smooth state changes.
# Styles for the .container class:
- background: Applies a linear gradient background with colors blueviolet and lightgreen at a 45-degree angle.
- padding: Adds padding of 15 pixels on the top and bottom, and 9% of the container's width on the left and right.
- padding-bottom: Adds additional bottom padding of 100 pixels.
- Styles for the heading inside the .container class:
- text-align: Aligns the text to the center.
- padding-bottom: Adds padding to the bottom of the heading.
- color: Sets the text color to white.
- text-shadow: Adds a text shadow for a visual effect.
- font-size: Sets the font size to 50 pixels.
  # This block styles the .box-container class within the .container class:
- display: grid;: Specifies that the container should be displayed as a grid layout.
- grid-template-columns: repeat(auto-fit, minmax(270px, 1fr));: Defines the grid layout for the columns. It uses the repeat() function to repeat the column pattern. The - auto-fit keyword instructs the browser to automatically fit as many columns as possible while maintaining a minimum width of 270 pixels (minmax(270px, 1fr)).
- gap: 15px;: Sets the gap (space) between grid items to 15 pixels.
  # This line applies styles to the .box elements within the .box-container class within the .container class when they are being hovered over by the mouse.
- box-shadow: 0 10px 15px rgba(0, 0, 0, 0.3);: Adds a shadow effect to the box when hovered over. The parameters represent the horizontal offset (0), vertical offset (10px), blur radius (15px), and color (rgba(0, 0, 0, 0.3)).
- transform: scale(1.03);: Applies a scaling transformation to the box when hovered over, increasing its size by 3%.
  # This block of code applies styles to the .container class when the maximum viewport width is 768 pixels or less.
- padding: 20px;: Sets the padding of the container to 20 pixels on all sides when the viewport width is 768 pixels or less.
