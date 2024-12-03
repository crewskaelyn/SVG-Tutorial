## Creating Shapes

In this section, we'll learn how to create different shapes in SVG. By the end of this page, you'll be able to create basic geometric shapes, such as rectangles, circles, and polygons.  

---

## 1. Rectangles

Rectangles are one of the most common shapes in SVGs. Here's how to create a simple rectangle:  

```xml
<svg xmlns="http://www.w3.org/2000/svg" width="200" height="200">
  <rect x="20" y="20" width="150" height="100" fill="green" />
</svg>
```

<img src="./svgs/rectangle.svg" alt="Green Rectangle" />

### Explanation:  
 - `<rect>`: Defines a rectangle.
 - `x` and `y`: The starting coordinates (top-left corner) of the rectangle. 
 - `width` and `height`: Define the size of the rectangle.
 - `fill`: The color to fill the rectangle.

---

## 2. Circles

Circles are created with the `<circle>` element. Here's an example:  

```xml
<svg xmlns="http://www.w3.org/2000/svg" width="200" height="200">
  <circle cx="100" cy="100" r="50" fill="red" />
</svg>
```

<img src="./svgs/cricle.svg" alt="Red Circle">

### Explanation:  
 - `<circle>`: Defines a circle/
 - `cx` and `cy`: The center coordinates of the circle.  
 - `r`: The radius of the circle.
 - `fill`: The color to fill the circle. 

---



---

## **Next Steps**

Now that you've learned how to create more basic shapes, you can move on to adding colors, gradients, and text in your SVGs!  
**[Next: Text and Colors](./5text-and-colors.md)**.  

- Or revisit the **[Viewing SVGs Guide](./3viewing-svg.md)**.  
- Or return to the **[Home Page](./README.md)**.  