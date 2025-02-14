# 🌟 My Portfolio Website

A personal portfolio website crafted with HTML, CSS, and JavaScript. It presents my skills, projects, and contact details in a sleek, user-friendly interface, featuring both light and dark mode options for an enhanced experience.

# 🚀 Key Features
Home Page – A brief introduction about myself.

About Page – Insights into my background, journey, and interests.

Skills Page – A display of my technical and professional expertise.

Projects Page – Showcasing my completed and ongoing projects.

Contact Page – A simple way for visitors to reach out to me.

Dark/Light Mode – Toggle between light and dark themes for better usability.

# 🛠️ Technologies Used
HTML – Structuring the website.

CSS – Enhancing the design and visual appeal.

JavaScript – Adding interactivity, such as theme switching and dynamic content.

## 📂 File Structure

•⁠  ⁠*Img* – images

•⁠  ⁠*CSS* – CSS styles

•⁠  ⁠*JS* – JS files

•⁠  ⁠*HTML* – Main index html page

# How to Run the Project Locally
Step 1: Open your terminal or command prompt.

Step 2: Navigate to your project folder:

Step 3:
```bash
cd path/to/your/project
```

Step 4: Initialize a Git repository:
```bash
git init
```

Step 5: Add all files to the staging area:
```bash
git add .
```

Step 6: Commit the files:
```bash
git commit -m "Initial commit"
```

Step 7: Link your local repository to GitHub:
```bash

```

Step 8: Push the files to GitHub:
```bash
git push -u origin main
```



# Challenges Faced & How You Overcame Them
1. CSS Not Loading Properly

Issue: Styles were not applied when viewing the site in the browser.
Solution:

- Checked if the CSS file path was correct and used relative paths

```bash
<link rel="stylesheet" href="style.css">
```

- Ensured the CSS file was saved and correctly linked in index.html.


# 2. JavaScript Not Working

Issue: JavaScript functions weren’t executing properly.

Solution:

Opened DevTools (F12 → Console) to check for errors.

Used console.log() to debug.

Ensured the script was properly linked in index.html:

```bash
<script src="script.js"></script>
```

- Placed the script before closing the <body> tag or used defer to ensure it loads after the page:

```bash
<script src="script.js" defer></script>
```

# 3. Images or Links Not Showing
Issue: Images or links were broken when viewed on GitHub Pages.

Solution:

Used relative paths instead of absolute paths. Example:

```bash
<img src="assets/images/profile.jpg" alt="Profile">
```

# 4. GitHub Pages Not Updating
Issue: The website didn’t reflect the latest version after making changes and pushing updates.

Solution:

Cleared the browser cache (Ctrl + Shift + R or Cmd + Shift + R on Mac).

Made sure all changes were committed and pushed.

```bash
git add .
git commit -m "Updated portfolio"
git push origin main
```

Verified that GitHub Pages was enabled in the repository settings




# 🌍 Live Demo

https://fayaal-paakeer.github.io/My-Portflio

# 👨‍💻 Created By

Fayaal Paakeer
