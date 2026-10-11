# Week 1 — Google-style Homepage Clone

A beginner-friendly HTML and CSS practice project. It is a visual learning exercise, not an official Google service. The search form does not perform a real search.

## Files
- `index.html` — page structure and text
- `styles.css` — colors, spacing, layout, responsiveness, and focus states

## How to open
1. Keep both files in the same folder.
2. Open `index.html` in a browser.
3. Edit the HTML for content and `styles.css` for appearance.
4. Refresh the browser after saving changes.

## Layout choices
- Flexbox is used for the overall page, header, search bar, buttons, and footer.
- `min-height: 100vh` and `flex: 1` help keep the footer near the bottom.
- A media query changes spacing and footer layout on smaller screens.
- The search input has an accessible label, and links/buttons have visible keyboard-focus styles.

## One challenge solved
Keeping the footer near the bottom without using a fixed position, while allowing the page to scroll naturally on short screens.

## Make it your own before submission
Change at least a few colors, spacing values, button labels, or footer links. Then explain in your own words what `display: flex`, `gap`, `padding`, and `@media` do. Capture screenshots at mobile and desktop widths if your mentor requires them.
