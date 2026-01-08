# LAB 6 – Answers

1. res.render(view, data) renders an EJS template with the given data and sends the generated HTML to the browser.

2. <%= %> outputs escaped HTML to prevent XSS, while <%- %> outputs raw HTML without escaping.

3. Express looks for EJS templates in the folder specified by app.set("views"), which is the views/ directory.
