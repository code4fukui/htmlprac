# ES-Jam: Web Programming Dojo (htmlprac)

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A simple, browser-based editor for learning and practicing HTML, powered by the Monaco Editor.

## Demo

Try it live: **[https://code4fukui.github.io/htmlprac/](https://code4fukui.github.io/htmlprac/)**

## Features

-   **Code Editor**: Monaco-powered editor with HTML syntax highlighting.
-   **On-Demand Preview**: Render your HTML in a side-by-side preview pane by clicking "見てみる" (Preview) or pressing `Ctrl+S`.
-   **File Handling**: Save your work as a timestamped `.html` file and load local files back into the editor.
-   **Auto-Correction**: Automatically fixes common HTML mistakes (e.g., full-width characters to half-width) when you preview the code.
-   **Load from URL**: Pre-load code into the editor from an external file using a query parameter.
-   **Share via URL**: Share code snippets directly by encoding them in the URL hash.

## Usage

1.  **Open the [demo page](https://code4fukui.github.io/htmlprac/).**
2.  **Write Code**: Type your HTML into the editor panel on the left.
3.  **Preview**: Click the **見てみる** (Preview) button or press `Ctrl+S` to update the rendered output in the right-hand panel.
4.  **Save/Load**:
    -   Click **SAVEする** (Save) to download your code as an `.html` file.
    -   Click **LOADする** (Load) to open a local `.html` file in the editor.

### Loading Code via URL

You can pre-populate the editor with code using URL parameters.

-   **From an external file:**
    Use the `url` query parameter to fetch and load code from a raw text or HTML file.
    ```
    https://code4fukui.github.io/htmlprac/?url=URL_TO_YOUR_RAW_HTML_FILE
    ```

-   **From the URL hash:**
    Embed HTML directly into the URL's hash to share small snippets.
    ```
    https://code4fukui.github.io/htmlprac/#<h1>Hello%20from%20URL!</h1>
    ```

## Attribution

This project is created and maintained by [Code for FUKUI](https://github.com/code4fukui/htmlprac).

## License

MIT License — see [LICENSE](LICENSE).