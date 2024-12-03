## Animating SVGs

SVGs can be animated using the `<animate>` element or CSS. This section covers basic animation techniques to bring your SVGs to life.  

---

## 1. Using the `<animate>` Element

You can animate attributes in SVG by using the `<animate>` element. Here's an example where we animate the `x` position of a rectangle:

```xml
<svg xmlns="http://www.w3.org/2000/svg" width="400" height="200">
  <rect x="10" y="50" width="100" height="100" fill="purple">
    <animate attributeName="x" from="10" to="300" dur="3s" repeatCount="indefinite" />
  </rect>
</svg>
```

### Explanation: 
- `<animate>`: Defines the animation.
- `attributeName`: The attribute to animate (e.g., `x`, `y`, `width`, `height`, etc.).
- `from` and `to`: The starting and ending values for the animation.
- `dur`: Duration of the animation.
- `repeatCount`: Specifies how many times the animation should repeat (e.g., `indefinite` for an infinite animation).

---

## 2. Using CSS for Animation

CSS animations can be applied to SVGs just like any HTML element. Here's an example of animating a circle:

```html
<svg xmlns="http://www.w3.org/2000/svg" width="200" height="200">
  <circle cx="100" cy="100" r="50" fill="green" class="animate-circle" />
</svg>

<style>
  .animate-circle {
    animation: moveCircle 3s infinite;
  }

  @keyframes moveCircle {
    0% { cx: 100; cy: 100; }
    50% { cx: 200; cy: 100; }
    100% { cx: 100; cy: 100; }
  }
</style>
```

### Explanation:
- **CSS Animation**: Using `@keyframes` to define the animation sequence.
  - `animation`: Applies the animation to the SVG element.
  - `@keyframes`: Defines the animation steps over time.


---

## **Next Steps**

Now that you've learned how to animate SVGs, you can experiment with more complex animations andinteractions!  
**[Next: Example Projects](./7examples.md)**.  

- Or revisit the **[Text and Colors Guide](./5text-and-colors.md)**.  
- Or return to the **[Home Page](./README.md)**.  