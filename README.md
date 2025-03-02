# Website Designs

## Overview
Website designs using tailwind and pure CSS.

## Project Setup
1. **Initialize npm**: 
   - Run `npm init` to create a `package.json` file.
   - This file contains metadata about the project and its dependencies.

2. **Install Dependencies**:
   - Use `npm install tailwindcss @tailwindcss/cli` to add necessary libraries and frameworks through cli.
   -  `@import "tailwindcss";` to add tailwind for server-side development in `input.css` file.
   - Start the Tailwind CLI build process
    Run the CLI tool to scan your source files for classes and build your CSS. 
    `npx @tailwindcss/cli -i ./input.css -o ./output.css --watch`

    - Start using Tailwind in your HTML
     Add your compiled CSS file to the <head> and start using Tailwind’s utility classes to style your content.
       <link href="./output.css" rel="stylesheet">

3. **Project Structure**:
   - Describe the directory structure of your project.
   - Example:
     ```
     /project-root
     ├── node_modules
     ├── src
     │   ├── E-guru Landing     ├──01-e-guru.html
     │   └── Hospital Landing   ├──02-hospital-landing.html
     │   └── Bike Landing       ├──03-Bike-landing.html
     │   └── NFT Landing        ├──04-NFT-landing.html
     │   └── PixLab Landing     ├──05-pixlab-landing.html
     ├── input.css
     ├── output.css
     └── index.html
     ```

## Features Implemented
- List the features or functionalities you have implemented so far.
- Example:
  - Basic server setup using tailwindcss/cli.

## Running the Project
1. **Start the Server**:
   - Provide instructions on how to run the project.
   - Example: `node src/index.js` or `npm start`.

## License
- Include the license information if applicable.