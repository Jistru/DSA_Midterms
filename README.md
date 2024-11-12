# React JS

## What is React JS?

- React.js is a tool for building websites and apps. Think of it like a set of Lego blocks that lets you quickly create parts of a website, like buttons, menus, or even entire pages. With React, you build these small pieces (called "components"), and React helps you put them together to create a dynamic, interactive experience.

- React is especially good at making websites that feel fast and respond quickly when you click, scroll, or type, because it only updates parts of the screen that actually change, not the whole page.

---

## Before setting up React, here are the things you must know about:

1. **Basic JavaScript Knowledge**

- Since React is a JavaScript library, having some understanding of JavaScript (like variables, functions, loops, and objects) will be helpful.
- It’s okay if you’re not an expert! React itself can help you learn more JavaScript along the way.

2. **A Code Editor**

- You’ll need a code editor to write and edit your React code. Some popular free editors are:

    - Visual Studio Code (highly recommended for React projects)
    - Atom
    - Sublime Text

3. **Node.js and npm**

- **Node.js:** React requires Node.js to run. Node is a program that lets you run JavaScript code outside a browser.
- **npm (Node Package Manager):** This comes with Node.js and lets you download and manage tools like React.
- **How to Install Node.js:**

    - Download the installer from [Node.js](https://nodejs.org/).

    - Follow the installation steps. You can check if it installed correctly by opening a terminal and typing:
        ```
        node -v
        ```
        ```
        npm -v
        ```

    - Both should give you version numbers, showing that Node and npm are ready to go.

4. **A Basic Understanding of HTML and CSS**

- React uses HTML and CSS to structure and style parts of the app. Knowing a bit about how HTML and CSS work will make using React much easier.

    Optional but Helpful:

- Browser DevTools: Familiarity with Chrome or Firefox Developer Tools (like inspecting elements) can help when troubleshooting issues with your app.
- Git (for version control): Git isn’t required, but it’s useful for managing changes, especially for bigger projects.

    Once you have these things, you’ll be ready to set up a new React app with Create React App!

---

## If you know some things whats written above, Here`s How to Set Up React JS

1. **Install Node.js (Needed for React)**

- First, you need Node.js. It’s a program that lets you use JavaScript outside of a browser and helps you download other tools.
- Go to Node.js website. and download the installer. Just click “Next” through the installation steps. (or you can just tap the Node.js above this section on Number 3.)

2. **Create a New React Project**

    - Once Node.js is installed, you can easily set up a React project using something called Create React App.

    **1. Open your terminal (or Command Prompt on Windows).**

    **2. Type this command:**
    ```
    npx create-react-app my-app
    ```
    - This command creates a new folder named my-app (you can name it anything you like).
    - It will set up everything React needs to run.

**3. Go into Your Project Folder**
- Move into the project folder by typing:
    ```
    cd my-app
    ```
**4. Start Your Project**
- Start the React app with:
    ```
    npm start
    ```
- This will open a new browser window at http://localhost:3000 where you’ll see a welcome page from React.

**5. Customize Your App**
- Open the my-app folder in your code editor (such as Visual Studio Code).
- Look for src/App.js. This is the main file where you can start adding or changing text to see it update in real-time on the page.

---

## In short
1. Install Node.js
2. Run npx create-react-app my-app
3. Go into the folder with cd my-app
4. Start the app with npm start
This is how you get started with React! From here, you can add buttons, text, images, and more to build your app.