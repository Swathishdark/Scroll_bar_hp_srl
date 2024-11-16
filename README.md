# Ticker Scrolling Updates with Cards

This project showcases a vertical scrolling ticker for displaying update cards. Each card includes an icon, update details, and a clickable link.

---

## Features
- **Scrolling Ticker**: Smooth vertical scrolling of updates.
- **Pause on Hover**: Scrolling stops when the user hovers over the ticker.
- **Clickable Links**: Each update links to relevant content.
- **Responsive Design**: Cards are styled with rounded corners and a light shadow for a modern look.

---

## Setup and Usage
1. Copy the HTML code into a file and save it as `index.html`.
2. Open the file in your browser to view the scrolling ticker.
3. Customize the update cards by editing the `update-card` divs.

---

## Code Structure

### HTML
```html
<div class="ticker">
  <div class="ticker-content">
    <div class="update-card">
      <img src="icon_url.png" alt="Icon">
      <div class="card-content">
        <span class="update-text">
          <a href="link_url">Update Title</a>
        </span>
        <span class="update-text-dis">Update Description</span>
        <span class="update-date">Updated on: DD-MM-YYYY</span>
      </div>
    </div>
    <!-- Add more cards as needed -->
  </div>
</div>
