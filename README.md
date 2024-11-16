Vertical Scrolling Ticker with Update Cards
Overview
This project creates a vertical scrolling ticker using HTML and CSS. The ticker displays a list of updates in a card format, complete with an image, update text, description, and update date. The content scrolls automatically, and the scrolling pauses when the user hovers over the ticker.

Features
Vertical Auto-Scrolling: The updates scroll smoothly in a vertical direction.
Card Design: Each update is displayed as a card with a rounded corner and subtle shadow for a polished look.
Hover Interaction:
Scrolling pauses when the user hovers over the ticker.
Highlighted background appears on the hovered card.
Responsive Design: Suitable for sidebar integration and adaptable across different screen sizes.
Links and Icons: Each update can include links and icons for further actions.
File Structure
HTML: Structure for the ticker and its updates.
CSS: Styling for the ticker, cards, and animations.
Usage
Prerequisites
A modern web browser.
Hosting environment (optional for deployment).
Installation
Copy the HTML code into a .html file.
Open the file in a browser.
Customization
Update Content:
Modify the <div class="update-card"> blocks to add/update content.
Each card contains:
An img tag for the icon.
Text with an embedded hyperlink.
Scroll Speed:
Adjust the animation: scroll 10s linear infinite; property in CSS to control the scrolling speed. For example:
10s: Faster scroll.
20s: Slower scroll.
Ticker Width:
Modify the width property in .ticker to adjust its size.
Deployment
Host the .html file on a local server (e.g., using Live Server in VS Code) or deploy to a web server.
Embed the ticker into an existing webpage by copying the HTML and CSS into your project.
Code Breakdown
HTML
The structure consists of:

A container (<div class="ticker">) for the scrolling ticker.
Individual cards (<div class="update-card">) containing:
Image: Circular icon (<img>).
Text: Hyperlinked update description.
CSS
Key Elements
Ticker Styling:
Fixed height and width for controlled scrolling area.
Positioned to the right for sidebar alignment.
Card Styling:
Rounded corners and shadows for modern aesthetics.
Spacing and padding for clear layout.
Animations:
@keyframes scroll: Handles the vertical scrolling effect.
Hover interaction pauses the animation.
Example
<div class="update-card">
  <img src="https://example.com/icon.png" alt="Icon">
  <div class="card-content">
    <span class="update-text">
      <a href="https://example.com">Update Title<br></a>
    </span>
    <span class="update-text-dis">Click to Learn More</span><br>
    <span class="update-date">Updated on: 01-01-2024</span>
  </div>
</div>
Notes:
Ensure the images are accessible via the provided URLs.
For a dynamic ticker, consider integrating JavaScript or APIs to fetch updates dynamically.
