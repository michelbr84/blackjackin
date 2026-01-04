# Royal Blackjack ♠️

A premium, modern, and immersive web-based Blackjack experience built with React.

![Royal Blackjack](img/screenshot.png) <!-- You might want to add a screenshot here later -->

## Features

*   **Premium Visuals**: Deep emerald and gold aesthetic for a high-stakes casino feel.
*   **Smooth Animations**: Fluid card dealing and interface transitions.
*   **Response Design**: Optimized for both desktop and mobile play.
*   **React Architecture**: Built using a component-based architecture for maintainability.

## How to Run

1.  **Clone the repository** (if you haven't already).
2.  **Start a local server**:
    Since this is a static app using JSXTransformer (for dev), it needs to be served over HTTP.

    Using Python 3:
    ```bash
    python -m http.server 8000
    ```
    
    Using Node (http-server):
    ```bash
    npx http-server -p 8000
    ```

3.  **Open in Browser**:
    Navigate to `http://localhost:8000`

## Project Structure

*   `js/all-components.js`: Contains the Main React components (Table, Hand, Card, Interface).
*   `css/style.css`: Modern CSS styling (Casino Theme).
*   `index.html`: Main entry point.

## Legacy Context

This project started as a "React JS Jumpstart" tutorial to demonstrate React basics. It has since been modernized into a full-fledged game experience.

---

> **Original Tutorial Credits**:
> React JS Jumpstart by [edgeuplink](http://edgeuplink.net).