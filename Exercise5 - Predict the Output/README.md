## Scenario A

### What color is the text?
Red

### Is it underlined?
Yes

### Is it aligned left, center, or right?
Center

### Explain the logic behind your three answers.
- It is red because the inline style has higher priority than the external stylesheet.
- It is underlined because the external stylesheet applies `text-decoration: underline`.
- It is centered because the inline style overrides the stylesheet rule and sets `text-align: center`.

## Scenario B

### What font family will paragraphs use?
Arial, sans-serif

### Are `#333333` and `rgb(51, 51, 51)` the same color? Show your math/explanation.
Yes, they are the same color.

#### Math / Explanation
- `#333333` is a hexadecimal color code where each pair of digits represents red, green, and blue.
- `33` in hex converts to decimal as `(3 × 16) + 3 = 51`.
- That gives RGB values of `rgb(51, 51, 51)`.

### If you remove the entire `p` rule, what font family will paragraphs use and why?
Paragraphs will use `Poppins, sans-serif` because the `body` rule sets that font family and `font-family` is inherited by child elements unless a more specific rule overrides it.

## Scenario C

### What color does the `<h1>` end up?
`hsl(240, 100%, 50%)` (blue)

### Why doesn't the first rule apply?
Because the second rule appears later in the stylesheet with the same selector and specificity, so it overrides the first.

### What CSS principle does this demonstrate?
The cascade/source order rule: when selectors have equal specificity, the later rule wins.
