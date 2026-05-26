# Eid Mubarak Festival Effect

A simple animated Eid greeting webpage built with **HTML**, **CSS**, and **JavaScript**.  
The page displays an Eid image with a 3D floating effect, glowing background, stars, fireworks particles, and mouse movement interaction.

## Live Demo

After publishing the project with GitHub Pages, add your live link here:

```text
https://your-username.github.io/eid-mubarak/
```

## Preview

![Eid Mubarak Preview](image.PNG)

## Features

- Full-screen animated Eid greeting page
- 3D floating image effect
- Fireworks particle animation using HTML Canvas
- Twinkling star background
- Mouse movement interaction
- Responsive design for desktop and mobile screens
- No external libraries required

## Project Structure

```text
eid-mubarak/
├── index.html
├── image.PNG
└── README.md
```

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Canvas API

## How to Run Locally

1. Download or clone the project.
2. Open the project folder.
3. Double-click `index.html` to open it in your browser.

Or run it using VS Code:

1. Open the folder in Visual Studio Code.
2. Install the **Live Server** extension.
3. Right-click `index.html`.
4. Choose **Open with Live Server**.

## How to Upload to GitHub

### Option 1: Using GitHub Website

1. Go to GitHub and create a new repository.
2. Name it:

```text
eid-mubarak
```

3. Keep it **Public** if you want to publish it with GitHub Pages.
4. Do not add another README because this project already has one.
5. Upload these files:
   - `index.html`
   - `image.PNG`
   - `README.md`
6. Click **Commit changes**.

### Option 2: Using Git Commands

Open the project folder in the terminal, then run:

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/your-username/eid-mubarak.git
git push -u origin main
```

Replace `your-username` with your GitHub username.

## How to Publish with GitHub Pages

1. Open the repository on GitHub.
2. Go to **Settings**.
3. Open **Pages** from the left sidebar.
4. Under **Build and deployment**, choose:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/root**
5. Click **Save**.
6. Wait a few minutes, then GitHub will give you a live website link.

## Important Notes

- Keep the image file name exactly as `image.PNG` because the HTML file uses this name.
- If you rename the image, update this line inside `index.html`:

```html
<img src="image.PNG" class="festivalImage" alt="عيد أضحى مبارك">
```

## Author

Created by Basel Ziada.
