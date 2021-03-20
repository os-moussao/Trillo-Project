# Takeaways

\*\* Why using custom CSS variables instead of sass variables:

- They can be manipulated in javascript
- We can edit them in dev tools
- It's easier to use them in the calc() function
- Css variables cascade and they are inherited

\*\* Why using SVGs (Scalable Vector Graphics), instead of icon fonts, is considered as a best practice:

- Icon fonts fail more often that you think, and the browser displays a blank square in that case, which is not good.
- More often, screen readers for blind people fail to read icon fonts
- https://icomoon.io/ is a better app to generate SVGs
