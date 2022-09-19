# Card System

<p float="center">
    <img src="screenshot-lg.png" alt="Screenshot" height="400" />
</p>

Card System built with **HTML** and **CSS** in combination with **BEM methodology**

## Technologies:

* HTML
* CSS

## Tools:

* VSCode

## Setup (Locally)

* Make a project folder
`mkdir card-system`
* CD into the project folder
`cd card-system`
* Install TailwindCSS
`npm install -D tailwindcss`
* Create Tailwind Configuration File
`npx tailwindcss init`
* In tailwind.config.js, add the following to the content array:
`content: [".src/**/*.{html,js}"]`
* Create `src` folder inside `card-system`
* Inside `src` create `index.html` and `input.css` files
* Add the following directives to the `input.css` file:
     ```
        @tailwind base;
        @tailwind components;
        @tailwind utilities;
    ```
* Compile CSS (Ensure you are in the project root directory):
`npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch`
* In `index.html`, link to the CSS like `<link href="../dist/output.css" rel="stylesheet">`
* Right click on `index.html` and select `open with live server`
* If no live server, open VSCode extension, search for "live server" extension and install it. You might need to restart VSCode for the change to take effect.

## Running the Project Locally

* Make a project folder
`mkdir card-system`
* CD into the project folder
`cd card-system`
* `git clone https://github.com/alain-kubwayo/card-system.git`
* `npm install`
* Open `index.html` with Live Server to view it in the browser

