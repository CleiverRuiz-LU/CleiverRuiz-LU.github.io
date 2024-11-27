# How to Create a GitHub.io Page

This guide explains how to set up and host your personal webpage using GitHub Pages, with implementation in VSCode.

---

## Steps to Create a GitHub.io Page

1. **Create a GitHub Repository**:
   - Go to [GitHub](https://github.com) and log in.
   - Create a new repository named `<your-username>.github.io` (replace `<your-username>` with your GitHub username).
   - Make sure the repository is public.

2. **Clone the Repository**:
   - Open a terminal or Git Bash and clone the repository:
     ```bash
     git clone https://github.com/<your-username>/<your-username>.github.io.git
     ```

3. **Add Your Webpage Files**:
   - Inside the cloned repository, add an `index.html` file. This file will act as your homepage.
   - Optionally, include CSS, JavaScript, or images in the same directory or organized in folders.

4. **Push Your Changes to GitHub**:
   - Stage and commit your files:
     ```bash
     git add .
     git commit -m "Initial commit"
     ```
   - Push the changes to your GitHub repository:
     ```bash
     git push origin main
     ```

5. **Access Your Website**:
   - Visit `https://<your-username>.github.io` in your browser. Your website should be live.

---

## VSCode Implementation

To streamline development, follow these steps to use VSCode for editing and previewing your GitHub Pages site:

### Install Required Extensions
Before pushing your code to GitHub, install the following extensions in VSCode:

1. **Live Preview**:
   - Install the [Live Preview extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode.live-server).
   - This extension allows you to preview your webpage within VSCode.

2. **Live Server**:
   - Install the [Live Server extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer).
   - This extension provides a local development server for testing your webpage in real time.

---

### Using the Extensions

#### Live Preview:
1. Open the Command Palette in VSCode (`Ctrl+Shift+P` or `Cmd+Shift+P` on Mac).
2. Run the following command:
    ```bash
     > Live Preview: Start Server Logging
     ```
3. Your webpage will open in a built-in VSCode browser.

#### Live Server:
1. Open your `index.html` file in VSCode.
2. Right-click inside the editor and select `Open with Live Server` (or click "Go Live" in the bottom-right corner of the VSCode window).
3. Your browser will open with a live preview of your webpage.

# Example of My Website

Below is an example of how the website will look:

![Website Example](/images/README_Website_example.png)



With this guide, you should be able to successfully create and host your GitHub.io page while leveraging the powerful features of VSCode for development.
