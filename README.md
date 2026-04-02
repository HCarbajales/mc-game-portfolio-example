# Game Design Portfolio - TECH 295 Example

A static portfolio website template for Montgomery College TECH 295 students to showcase their tabletop and mixed media game design projects.

**Live Demo**: [View on GitHub Pages](#https://hcarbajales.github.io/mc-game-portfolio-example/) *(update with your GitHub Pages URL after deployment)*

## What This Is

This is an example portfolio website built with plain HTML, CSS, and JavaScript. It demonstrates the structure, content, and presentation quality expected for the TECH 295 Website Portfolio assignment (10% of your grade).

## Portfolio Requirements Checklist

Your portfolio must include:

- [ ] **Home/About page** - Introductory info about you and your academic/career goals
- [ ] **Games page** - For each game you created:
  - [ ] Working link to playable game (Itch.io or AR app)
  - [ ] At least 3 screenshots highlighting the best parts
  - [ ] Text description of your game (can use your GDD)
  - [ ] Links to your GDD, flowcharts, and mockup designs
  - [ ] Video playthrough (YouTube or Vimeo embed)
- [ ] **Other Work page** - Work from other gaming-related classes (art, animation, programming)

## How to Use This Template

### Option 1: Fork on GitHub (Recommended)

1. Click **Fork** on this repository
2. Go to **Settings > Pages** and set Source to `main` branch
3. Your site will be live at `https://yourusername.github.io/repo-name/`
4. Edit the HTML files to replace the sample content with your own

### Option 2: Download and Edit Locally

1. Click **Code > Download ZIP**
2. Extract and edit the HTML files in any text editor
3. Open `index.html` in your browser to preview
4. Upload to your own hosting (WordPress, GitHub Pages, etc.)

## File Structure

```
mc_game_portfolio_example/
  index.html          <- About/Home page
  games.html          <- Game projects with screenshots, videos, docs
  other-work.html     <- Work from other classes
  css/
    style.css         <- All styling (dark theme, responsive)
  js/
    main.js           <- Mobile nav toggle, active page highlighting
  images/             <- Put your screenshots and photos here
```

## Customizing Your Portfolio

### Replace Sample Content

1. **index.html** - Update your name, bio, skills, and LinkedIn link
2. **games.html** - Replace the sample game projects with your actual TECH 295 projects
3. **other-work.html** - Add your work from TECH 190, TECH 290, GDES, and other courses

### Add Your Screenshots

1. Save your screenshots to the `images/` folder
2. Replace the placeholder `<div class="gallery-placeholder">` blocks with `<img>` tags:
   ```html
   <div class="gallery-item">
     <img src="images/my-screenshot.png" alt="Description of screenshot">
     <div class="gallery-caption">Caption text here</div>
   </div>
   ```

### Embed Your Videos

Replace the YouTube iframe `src` URL with your own video ID:
```html
<iframe src="https://www.youtube.com/embed/YOUR_VIDEO_ID" ...></iframe>
```

### Link Your Documents

Update the `href="#"` placeholders in the documentation links to point to your actual GDD, flowchart, marketing plan, and slides (hosted on Google Drive, Dropbox, etc.).

## Deploying to GitHub Pages

1. Create a new repository on GitHub
2. Push this code to the repository
3. Go to **Settings > Pages**
4. Under "Source", select **Deploy from a branch**
5. Choose `main` branch and `/ (root)` folder
6. Click Save
7. Your site will be available at `https://yourusername.github.io/repository-name/`

## Privacy Reminder

- Do NOT include your birth date, SSN, phone number, or home address
- Email and LinkedIn are sufficient for contact information
- Be thoughtful about what personal information you share publicly

## Rubric Reference

| # | Feature | Points |
|---|---------|--------|
| 1 | Overall Quality - professional, high-quality images, descriptive text | 2 |
| 2 | Organization & Layout - clear navigation, easy to find content | 1 |
| 3 | Grammar, Spelling, Formatting, Citations | 1 |
| 4 | Text - clear, concise, explains design process | 1 |
| 5 | Screenshots - at least 3 per game, good variety | 1 |
| 6 | Videos - engaging, shows design elements, includes audio | 1 |
| 7 | Game - links to playable games with instructions | 1 |
| 8 | Documents - GDDs, flowcharts, planning materials | 1 |
| 9 | Other assets - work from other classes | 1 |
| | **Total** | **10** |
