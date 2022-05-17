# Go through this repository thoroughly

## Coding Standards to Maintain

1. Folder Structure:
2. Naming conventions:
    - React UI component’s names should be PascalCase. <br>
    Eg: HomePage.js
    - All other helper files should be camelCase. <br>
    Eg: dateFormatter.js
    - All the folder names should be camelCase
    - CSS files should be named the same as the component PascalCase. Global CSS which applies to all components should be placed in index.css and should be named in camelCase
    - CSS variables should be defined in index.css
    - Font imports should be done in index.css
3. Codestyle:
    - No hardcoded values, use constants values.
    - Avoid multiple if/else and nested blocks.
    - No commented out code.
    - Add necessary comments.
    - Remove all console.log()
    - Treat props as read-only. Do not try to modify them
    - No DRY violations. Create utility files to avoid duplicate code
4. CSS:
    - Use classNames everywhere. Do not use html tags to style.
    - Use Hex color codes #000 unless using rgba().
    - Avoid absolute positioning.
    - Use flexbox.
    - Avoid !important unless absolutely necessary.
    - Do not animate width, height, top, left and others. Use transform instead.
    - Avoid inline styles unless necessary.
    - Use BEM naming convention