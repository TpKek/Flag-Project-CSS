# Flag Project - CSS

A CSS recreation of the Laos national flag, built using pure CSS positioning and nested selectors. This project demonstrates how CSS specificity and positioning can create complex visual designs.

## About

The flag of Laos consists of three horizontal stripes (red, blue, red) with a white circle in the center. This project recreates the flag using only CSS - no images required!

## What I Learned

This project taught me fundamental CSS concepts:

- **CSS Positioning**: Using `position: absolute` for precise element placement
- **Nested Selectors**: Targeting elements with `.flag > div > div` specificity
- **CSS Specificity**: Understanding how selector combinations override styles
- **Border Radius**: Creating perfect circles with `border-radius: 50%`
- **Color Values**: Working with hex color codes
- **Box Model**: Understanding width, height, and positioning relationships

## Tech Stack

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

| Technology | Purpose                            |
| ---------- | ---------------------------------- |
| HTML5      | Minimal nested div structure       |
| CSS3       | All visual styling and positioning |

## Flag Colors

| Element            | Color | Hex Code  |
| ------------------ | ----- | --------- |
| Top/Bottom Stripes | Red   | `#CE1126` |
| Middle Stripe      | Blue  | `#002868` |
| Center Circle      | White | `white`   |

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/TpKek/Flag-Project-CSS.git
   cd Flag-Project-CSS
   ```

2. Open in browser:
   - Simply open `index.html` in any modern web browser

## Project Structure

```
Flag-Project-CSS/
 index.html       # Flag structure with embedded CSS
 goal.png         # Reference design
 README.md        # This file
```

## Key CSS Concepts

```css
/* Nested selector targeting */
.flag > div {
  background-color: #002868;
  position: absolute;
  top: 150px;
}

.flag > div > div {
  background-color: white;
  border-radius: 50%;
}
```

## Challenge

The project includes a challenge: create the flag without adding any classes, IDs, or new HTML elements - using only CSS specificity to target the correct elements!

## Author

**Bertin Dreyer**

- GitHub: [@TpKek](https://github.com/TpKek)

---

CSS can paint too!
