# Interactive Mouse Coloring Game 🎨🐭🧀

A fun, interactive coloring game built with HTML, CSS, and JavaScript using the Canvas API. Color in a cute mouse and a block of cheese using brush and fill tools!

![image-final](https://github.com/user-attachments/assets/420f9fb5-d83d-4c3f-9a2f-686bda4a890c)


**[Live Demo Link](https://darshil-lalchandani.github.io/coloring-game/)** 

## Features

*   **Brush Tool:** Color freely by clicking and dragging.
*   **Fill Tool (Paint Bucket):** Click within an enclosed area to fill it with the selected color.
*   **Extensive Color Palette:** ~100 color options available.
*   **Hover-Reveal Palette:** Color palette appears when hovering over the dedicated "Colors" button, keeping the interface clean.
*   **Scrollable Palette:** Palette panel is scrollable if colors overflow the fixed height.
*   **Custom Cursor:** Cursor changes shape and color to reflect the selected tool (brush/eraser/fill) and color.
*   **Responsive Canvas:** The canvas display scales with the container width.

## Technology Used

*   HTML5
*   CSS3
*   JavaScript (ES6+)
*   HTML Canvas API (`getContext('2d')`, `getImageData`, `putImageData`)

## How to Run Locally

**Important:** Due to browser security restrictions (`Cross-Origin Resource Sharing` - CORS), the **Fill Tool** (which uses `getImageData`) will **not** work if you simply open the `index.html` (or your file name) directly from your local filesystem (`file:///...`).

You **must** run this project using a local web server. Here are a few easy ways:

1.  **Using VS Code + Live Server Extension:**
    *   Install the "Live Server" extension by Ritwick Dey.
    *   Open the project folder in VS Code.
    *   Right-click on the HTML file (`index.html` or `game-gemini.html`) and select "Open with Live Server".

2.  **Using Python:**
    *   Make sure you have Python installed.
    *   Open your terminal or command prompt.
    *   Navigate (`cd`) to the project directory (where the HTML and image file are).
    *   Run the command:
        *   Python 3: `python -m http.server`
        *   Python 2: `python -m SimpleHTTPServer`
    *   Open your browser and go to `http://localhost:8000` (or the address shown in the terminal).

3.  **Using Node.js:**
    *   Make sure you have Node.js and npm installed.
    *   Open your terminal or command prompt.
    *   Install `http-server` globally (if you haven't already): `npm install -g http-server`
    *   Navigate (`cd`) to the project directory.
    *   Run the command: `http-server`
    *   Open your browser and go to `http://localhost:8080` (or the address shown).

## Deployment

1.  Push your code (HTML, image file) to a GitHub repository.
2.  Go to your repository settings on GitHub.
3.  Navigate to the "Pages" section (usually under "Code and automation").
4.  Under "Build and deployment", select "Deploy from a branch" as the source.
5.  Choose the branch you want to deploy from (e.g., `main` or `master`).
6.  Select the root folder (`/root`).
7.  Click "Save". GitHub will build and deploy your site. The link will appear on the Pages settings page after a minute or two.
