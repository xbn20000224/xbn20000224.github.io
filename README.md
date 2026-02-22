# Bingnan Xiao – Personal Academic Website

This is a static personal academic website for **Bingnan Xiao**, Ph.D. Candidate at Fudan University.

## How to Deploy on GitHub Pages

1. **Create a GitHub repository** named `xbn20000224.github.io`.

2. **Upload all files** in this folder to the root of that repository.
   The directory structure should look like:
   ```
   /
   ├── index.html
   ├── publications.html
   ├── education.html
   ├── css/
   │   └── style.css
   ├── images/
   │   └── (your profile photo, e.g., profile.jpg)
   └── README.md
   ```

3. **Go to your repository Settings** → **Pages** → set the source branch to `main` and the folder to `/ (root)`.

4. Your site will be live at `https://xbn20000224.github.io` within a few minutes.

## Adding Your Profile Photo

1. Place your photo (e.g., `profile.jpg`) in the `images/` folder.
2. In each HTML file, replace the placeholder block:
   ```html
   <div class="profile-photo-placeholder">
     <i class="fa fa-user"></i>
   </div>
   ```
   with:
   ```html
   <img src="images/profile.jpg" alt="Bingnan Xiao" class="profile-photo" />
   ```

## Pages

| Page | File | Description |
|------|------|-------------|
| Home | `index.html` | Biography, research interests, and recent news |
| Publications | `publications.html` | Full list of papers with full author lists and links |
| Education | `education.html` | Academic background and selected awards |
