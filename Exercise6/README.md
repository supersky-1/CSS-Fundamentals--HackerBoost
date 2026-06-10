## Checklist

- Did I include **two** Google Fonts `<link>` tags?
    * **Yes** - One for Playfair Display and one for Lato

- Is all CSS in the external file (nothing in `<head>` or `style=""`)?
    * **Yes** - All CSS is in coffee.css with no inline styles

- Did I use HSL for the heading color as specified?
    * **Yes** - `color: hsl(30, 80%, 25%);`

- Did I use a named color for the subheading?
    * **Yes** - `color: gray;`

- Did I use RGB for the paragraph color?
    * **Yes** - `color: rgb(50, 50, 50);`

- Is the second paragraph the only one with `word-spacing`? (How did you target it?)
   * **Yes** - I targeted it using `p:last-of-type` which selects the last `<p>` element regardless of what elements come before it
