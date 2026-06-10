# 1. Which color does the paragraph currently display? 
 ### Explain why by identifying which CSS method wins and the rule that governs this.
 
 The color currenetly displayed is **orange**.
 This is because;
* p { color: red; } is a regular stylesheet rule in the `<style>` block.
* style="color: orange;" is an inline style on the `<p>` element.
In CSS cascade order, inline styles have higher priority than stylesheet rules, so the browser applies **orange** instead of**red**.

# 2. Make the paragraph green 
### Add only one line of code. Where did you add it, and why does it override the others? 

I added it to the external css file **stlye.css**. It overrirded the initial inline style because of the *!important* syntax used. The *!important* has more priority over inline style elements

# 3. Now remove your one line. Change one existing value (not add new code) in the `<style>` block so the paragraph becomes blue. Is this possible? Explain your reasoning.

I removed the line in the external css file and changed the the named value in the inline stlye from **orange** to **blue** 