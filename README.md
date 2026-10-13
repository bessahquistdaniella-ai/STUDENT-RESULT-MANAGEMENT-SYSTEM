# ArrayWise — Student Result Management System

A responsive, static website demonstrating arrays as a data structure in a real-world student result management scenario.

## Features
- Includes 26 sample student records; add student names, IDs, and marks (0–100)
- Search records by name or student ID
- Filter pass/fail results (pass mark: 50)
- Remove a student record
- Automatically calculate class average, highest mark, and lowest mark
- Introduction explaining arrays and the Student Result Management System
- Five real-world applications of arrays: student results, banking, inventory, hospital management, and online examinations
- Educational sections explaining why arrays are necessary: efficiency, clarity, flexibility, reusability, and correctness
- Uses a JavaScript array in memory; no database, framework, or build step required

## Run locally
Open `index.html` in a web browser.

## Deploy on GitHub Pages
1. Create a GitHub repository.
2. Upload `index.html` and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under Build and deployment, select **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.
6. Wait for GitHub Pages to publish the site.

## Deploy on Vercel
1. Create a GitHub repository and upload these files.
2. In Vercel, choose **Add New → Project** and import the repository.
3. Since this is a static HTML site, no build command is needed. Leave the output directory blank/default or use the repository root.
4. Deploy.

## Important limitation
Student data is held only in the browser's JavaScript array. It resets on refresh and is not shared between users. This is intentional for demonstrating arrays only. Do not use real private student data in this demo.
