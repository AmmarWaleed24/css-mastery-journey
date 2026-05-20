# CSS Gradients Lesson 55

CSS gradients allow you to create smooth transitions between two or more colors. They are often used to enhance backgrounds, buttons, and UI elements. There are three main types of gradients in CSS:

## 1. Linear Gradient (`linear-gradient`)
A linear gradient creates a transition between colors along a straight line.

### Syntax:
```css
background: linear-gradient(direction, color1, color2, ...);
```
- `direction` (optional) → Specifies the angle or side where the gradient starts (e.g., `to right`, `to bottom`, `45deg`).
- `color1, color2, ...` → Defines the colors for the transition.

### Example:
```css
.gradient-box {
    width: 200px;
    height: 100px;
    background: linear-gradient(to right, red, blue);
}
```
This creates a gradient that transitions from red to blue from left to right.

## 2. Radial Gradient (`radial-gradient`)
A radial gradient spreads out from a central point, creating a circular or elliptical blend of colors.

### Syntax:
```css
background: radial-gradient(shape size at position, color1, color2, ...);
```
- `shape` (optional) → Can be `circle` or `ellipse`.
- `size` (optional) → Determines how far the gradient extends (e.g., `closest-side`, `farthest-corner`).
- `position` (optional) → Specifies the starting point (e.g., `center`, `top left`).

### Example:
```css
.gradient-box {
    width: 200px;
    height: 100px;
    background: radial-gradient(circle, red, blue);
}
```
This creates a circular gradient transitioning from red at the center to blue at the edges.

## 3. Conic Gradient (`conic-gradient`)
A conic gradient rotates colors around a central point, like a pie chart.

### Syntax:
```css
background: conic-gradient(color1 degree, color2 degree, ...);
```
- `colorX degree` → Specifies the color stop at a certain degree.

### Example:
```css
.gradient-box {
    width: 200px;
    height: 100px;
    background: conic-gradient(red, blue, green);
}
```
This creates a circular gradient where colors transition around a center point.

## Additional Gradient Features:
- **Multiple Color Stops** → You can add multiple colors to create complex effects.
  ```css
  background: linear-gradient(to right, red, yellow, green, blue);
  ```
- **Transparency** → Use RGBA or HSLA values for transparent gradients.
  ```css
  background: linear-gradient(to right, rgba(255, 0, 0, 0.5), rgba(0, 0, 255, 0.5));
  ```
- **Repeating Gradients** → Use `repeating-linear-gradient`, `repeating-radial-gradient`, or `repeating-conic-gradient` to create striped or tiled effects.
  ```css
  background: repeating-linear-gradient(45deg, red, yellow 10px, green 20px);
  ```

## Example Output:
![Screenshot 2025-02-19 095611](https://github.com/user-attachments/assets/d63bc380-19c6-433c-9f55-5f857f4cc233)
![maxresdefault](https://github.com/user-attachments/assets/23ed947c-cd4d-481f-a467-b9062230e122)

---

## License
This project is open-source. Feel free to use and modify it as needed.

## Author
[Ammar Waleed]  
**GitHub:** [https://github.com/AmmarWaleed24](https://github.com/AmmarWaleed24)  
**LinkedIn:** [www.linkedin.com/in/ammarwaleed22](www.linkedin.com/in/ammarwaleed22)
