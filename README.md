# CSS Positioning Example

This project demonstrates different CSS positioning techniques, including static, sticky, fixed, relative, and absolute positioning, along with a flexible layout.

## Technologies Used

- HTML
- CSS

## Project Structure

- **index.html**: Contains the basic structure of the webpage and uses multiple CSS positioning techniques.
- **style.css**: Defines the styling for the HTML elements, including various position properties such as `static`, `sticky`, `fixed`, `relative`, and `absolute`.

## CSS Positioning Explained

1. **Static**: This is the default position of an element in normal document flow. No additional CSS is required for this positioning.
   
2. **Sticky**: The element with class `.sticky-header` sticks to the top of the viewport when scrolled past a certain point.

    ```css
    .sticky-header {
        position: sticky;
        top: 10px;
    }
    ```

3. **Fixed**: The element with class `.fixed` stays in a fixed position relative to the viewport, even when scrolling.

    ```css
    .fixed {
        position: fixed;
        bottom: 0;
        right: -10px;
    }
    ```

4. **Relative**: The element with class `.relative` is positioned relative to its normal position, offset by `top` and `right` values.

    ```css
    .relative {
        position: relative;
        top: 50px;
        right: 50px;
    }
    ```

5. **Absolute**: The element with class `.absolute` is positioned relative to its closest positioned ancestor (if any), or the document body otherwise.

    ```css
    .absolute {
        position: absolute;
        right: 0;
        bottom: 10px;
    }
    ```

## How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/bhagwan06/css-position-.git
    ```
2. Open `index.html` in your browser to view the demo of various CSS positions.

