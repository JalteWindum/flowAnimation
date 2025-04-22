# Flow Animation Dashboard

## How to Run

### Option 1: Using Python (Recommended)
1. Open a terminal/command prompt in this folder
2. Run one of these commands (depending on your Python version):
   ```
   python -m http.server 8000
   ```
   or
   ```
   python3 -m http.server 8000
   ```
   or (Windows):
   ```
   py -m http.server 8000
   ```
3. Open your browser and go to: http://localhost:8000

### Option 2: Using Node.js
If you have Node.js installed:
1. Open a terminal/command prompt in this folder
2. Run:
   ```
   npx http-server
   ```
3. Open your browser and go to the URL shown in the terminal (usually http://localhost:8080)

### Option 3: VS Code
If you're using VS Code:
1. Install the "Live Server" extension
2. Right-click on index.html
3. Select "Open with Live Server"

The visualization should now show properly in your browser. 

## How to Update the Live Version (GitHub Pages)

1.  **Make changes** to `index.html`, `25040702.svg`, or other files locally.
2.  **Open a terminal** in this project folder.
3.  **Stage the changed files:**
    ```bash
    # Stage specific files (e.g., if you only changed index.html)
    git add index.html

    # Or stage all changed files
    git add .
    ```
4.  **Commit the changes** with a descriptive message:
    ```bash
    git commit -m "Describe your changes here"
    ```
5.  **Push the changes** to GitHub:
    ```bash
    git push origin master
    ```

GitHub will automatically update the live site at [https://jaltewindum.github.io/flowAnimation/](https://jaltewindum.github.io/flowAnimation/) within a couple of minutes. 