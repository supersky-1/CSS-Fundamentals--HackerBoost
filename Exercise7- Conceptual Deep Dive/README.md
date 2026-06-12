# Exercise 7 Answers

1. If HTML is the walls and framework, and CSS is the paint and furniture, trying to build a house using only CSS is impossible. CSS depends on HTML to define the actual elements and structure; without HTML there is nothing for CSS to style. A web browser needs HTML to know what content exists, and CSS can only decorate that content. So no HTML means no rooms, no doors, no windows, no walls, just a set of styling rules that have nothing to attach to.

2. One concrete scenario is a large e-commerce site with hundreds of product pages. If every page used inline CSS, updating a global branding change like the company’s new button color or font would require editing each page individually. That could take days, introduce inconsistent results, and risk broken pages if one update is missed. With external CSS, a single stylesheet change updates every page immediately, making the redesign fast, consistent, and far less error-prone.

3. In the first case, the paragraph ends up green because the second rule appears later in the stylesheet with equal specificity, so it overrides the first. In the second case, if the paragraph has the class `highlight`, the color will also be green. That happens because a class selector (`.highlight`) is more specific than a simple tag selector (`p`), so the class rule wins even if the tag rule comes first.

4. The lesson shows four different color formats because each one has practical advantages:
   - Named colors are easy to remember and use for basic colors like `gray` or `red`.
   - Hex codes are compact and widely supported, making them great for matching exact brand colors.
   - RGB is helpful when you want to think in red/green/blue values or adjust colors programmatically.
   - HSL is useful when you want to change lightness or saturation without recalculating all three RGB values. Each format gives developers a different way to express color depending on the task.
