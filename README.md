Boilerplates for HTML, CSS

This project includes basic boilerplates for HTML, CSS, and JavaScript to streamline the setup of a web development project. Below is a description of each boilerplate and how to use it within Visual Studio Code (VS Code).

Press Ctrl+Shift+P (or Cmd+Shift+P on macOS), and select Preferences: Configure User Snippets.
Save the html.json file, and now you can use the snippet in any HTML file by typing htmlcustom and pressing Tab.

{
    "Custom HTML Boilerplate": {
        "prefix": "htmlcustom",
        "body": [
            "<!DOCTYPE html>",
            "<html lang=\"en\">",
            "<head>",
            "    <meta charset=\"UTF-8\">",
            "    <meta name=\"viewport\" content=\"width=device-width, initial-scale=1.0\">",
            "    <meta http-equiv=\"X-UA-Compatible\" content=\"IE=edge\">",
            "    <title>${1:Document}</title>",
            "    <link rel=\"stylesheet\" href=\"${2:styles.css}\">",
            "    <script defer src=\"${3:scripts.js}\"></script>",
            "</head>",
            "<body>",
            "    ${4:<!---->}",
            "</body>",
            "</html>"
        ],
        "description": "My custom HTML boilerplate with styles.css and scripts.js"
    }
}

Press Ctrl+Shift+P (or Cmd+Shift+P on macOS), and select Preferences: Configure User Snippets.
Save the css.json file, and now you can use the snippet in any CSS file by typing csscustom and pressing Tab.

{
    "Custom CSS Boilerplate": {
        "prefix": "csscustom",
        "body": [
            "body {",
            "    font-family: ${2:sans-serif};",
            "    margin: 0;",
            "    padding: 0;",
            "    box-sizing: border-box;",
            "}",
        ],
        "description": "Boilerplate for styles.css file"
    }
}



