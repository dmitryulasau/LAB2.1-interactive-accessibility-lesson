# Reflection Questions

### 1. What accessibility enhancements were the most challenging to implement, and why?

The most challenging part was making interactive elements work well with both a keyboard and a screen reader. It is easy to build something that works with a mouse, but keyboard support, visible focus, and clear labels need extra attention. I also learned that adding ARIA is not always the solution. Choosing the correct semantic HTML element is usually a better starting point.

### 2. How do ARIA attributes improve the experience for users relying on assistive technologies?

ARIA gives assistive technologies extra information about an elements name, role, state, and relationships. For example, `aria-live` announces important updates. This makes interactive and dynamic interfaces easier to understand.

### 3. What tools did you use to check color contrast, and how did they help?

The WebAIM Contrast Checker and Color Contrast Checker by Coolors are useful for comparing text and background colors against WCAG requirements. Chrome DevTools and Lighthouse can also point out possible accessibility issues. These tools help identify text that may be difficult to read, but manual checks are still important. I learned not to choose colors based only on appearance and never to use color as the only way to show meaning.