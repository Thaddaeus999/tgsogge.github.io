# Thomas Gjersøe Sogge - Portfolio Website

A responsive portfolio website showcasing data science and machine learning projects.

## Files for Deployment

You need these files to deploy your portfolio:

1. **index.html** - Main portfolio page (already created)
2. **images/personal_picture.jpg** - Your personal photo
3. **README.md** - This file

## GitHub Pages Deployment Guide

### Step 1: Create a GitHub Repository

1. Go to [GitHub.com](https://github.com) and sign in
2. Click the green **"New"** button or the **"+"** icon in the top right
3. Name your repository: `your-username.github.io` (replace "your-username" with your actual GitHub username)
   - Example: If your username is "thaddaeus999", name it: `thaddaeus999.github.io`
4. Make sure it's set to **Public**
5. Check **"Add a README file"**
6. Click **"Create repository"**

### Step 2: Upload Your Files

**Method A: Using GitHub Web Interface (Easiest)**

1. In your new repository, click **"uploading an existing file"** or **"Add file" > "Upload files"**
2. Drag and drop or select these files:
   - `index.html` (the file I created for you)
   - Your personal picture (rename it to `personal_picture.jpg`)
3. Create a folder called `images` and put your photo inside it
4. Scroll down and write a commit message like "Add portfolio website"
5. Click **"Commit changes"**

**Method B: Using Git Commands (If you have Git installed)**

1. Clone your repository:
   ```bash
   git clone https://github.com/YOUR-USERNAME/YOUR-USERNAME.github.io
   cd YOUR-USERNAME.github.io
   ```

2. Copy your files into the folder:
   - Copy `index.html` to the root folder
   - Create an `images` folder and put your photo there as `personal_picture.jpg`

3. Add and commit your files:
   ```bash
   git add .
   git commit -m "Add portfolio website"
   git push origin main
   ```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on **"Settings"** tab (at the top of the repository)
3. Scroll down to **"Pages"** in the left sidebar
4. Under **"Source"**, select **"Deploy from a branch"**
5. Choose **"main"** branch and **"/ (root)"** folder
6. Click **"Save"**

### Step 4: Access Your Live Website

1. After a few minutes, your website will be available at:
   ```
   https://YOUR-USERNAME.github.io
   ```
2. GitHub will show you the URL in the Pages settings
3. It may take 5-10 minutes for changes to appear online

### Step 5: Update Your Website

To make changes later:

1. Edit files directly on GitHub (click the pencil icon on any file)
2. Or upload new files using the same upload process
3. Changes will automatically update your live website

## File Structure

Your repository should look like this:

```
your-username.github.io/
├── index.html
├── images/
│   └── personal_picture.jpg
└── README.md
```

## Important Notes

- Your repository name MUST be exactly `your-username.github.io` for the automatic URL to work
- Make sure your photo is named exactly `personal_picture.jpg` and placed in the `images` folder
- The website is fully responsive and will work on all devices
- Your contact form is already connected to your Formspree account

## Troubleshooting

- **Website not loading**: Wait 10 minutes after enabling Pages, then check again
- **Photo not showing**: Make sure the image is named `personal_picture.jpg` and in the `images` folder
- **Changes not appearing**: GitHub Pages can take a few minutes to update

Your portfolio website will be live and accessible to anyone with the URL once deployed!