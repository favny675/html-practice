# HMS Web App

This is a beginner-friendly HR Management System website built with only HTML and CSS.

## Pages
- `index.html` — Marketing/home page with multiple sections and images.
- `dashboard.html` — Simple dashboard page with a CSS-only sidebar and cards.
- `style.css` — All styles for both pages.

## How to Run
1. Open the folder in your code editor.
2. Open `index.html` in your browser.
3. Use the navigation to visit `dashboard.html`.

## Recommended CSS Order (Top to Bottom)
CSS is easier to read and maintain when it follows a consistent order. Use this
simple hierarchy so a beginner can quickly find styles:

1. **CSS variables / root tokens**
   - Put `:root` variables first (colors, spacing, shadows, fonts).
2. **Resets / base rules**
   - Universal selector `*`, `html`, `body`, `img`, `a`, `ul`, etc.
3. **Layout foundations**
   - Global containers, shared section layouts, grid helpers.
4. **Major page sections**
   - Header, nav, hero, about, features, stats, testimonials, footer.
5. **Components**
   - Buttons, cards, links, badges, panels, etc.
6. **Page-specific styles**
   - Dashboard-specific rules (sidebar, cards, panels).
7. **Utilities (optional)**
   - Small helper classes like `.text-center` or `.mt-2`.
8. **Responsive rules**
   - Media queries at the bottom.

## Why This Order Works
- It reads from general to specific.
- Global changes are easy to find at the top.
- Page-specific and responsive rules are easy to locate at the end.

## Customize Images
Images are currently placeholders. Replace each `img src` in `index.html` with
your own image links or local files.
