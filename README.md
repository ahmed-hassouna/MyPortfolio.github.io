# Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript, hosted on GitHub Pages.

## 🚀 Quick Start

### Step 1: Create GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the **"+"** icon (top right) → **"New repository"**
3. Name it: `your-username.github.io` (replace with your actual GitHub username)
4. Make it **Public**
5. Check **"Add a README file"**
6. Click **"Create repository"**

### Step 2: Upload Files

1. In your repository, click **"Add file"** → **"Create new file"**
2. Create each of these files by copying the content:
   - `index.html`
   - `style.css`
   - `script.js`
3. Commit each file with a message like "Add index.html"

### Step 3: Add Images

1. Create an **images** folder in your repository:
   - Click **"Add file"** → **"Create new file"**
   - Type `images/README.md` (this creates the folder)
   - Commit with message "Create images folder"

2. Upload your images:
   - Go into the `images` folder
   - Click **"Add file"** → **"Upload files"**
   - Upload these images:
     - `profile.jpg` - Your profile photo (square format, 500x500px recommended)
     - `project1.jpg` - Screenshot of project 1 (landscape, 1200x630px recommended)
     - `project2.jpg` - Screenshot of project 2
     - `project3.jpg` - Screenshot of project 3
     - `project4.jpg` - Screenshot of project 4
   - Commit with message "Add images"

**Don't have images yet?** You can:
- Use placeholder images from [Unsplash](https://unsplash.com) or [Pexels](https://pexels.com)
- Generate AI images with tools like [DALL-E](https://openai.com/dall-e-2) or [Midjourney](https://midjourney.com)
- Create simple graphics with [Canva](https://canva.com)
- Take screenshots of your actual projects

### Step 4: Enable GitHub Pages

1. Go to **Settings** → **Pages** (in the left sidebar)
2. Under **"Source"**, select **"Deploy from a branch"**
3. Choose **"main"** branch and **"/ (root)"** folder
4. Click **"Save"**
5. Wait 1-2 minutes for deployment

### Step 5: View Your Site

Your site will be live at: `https://your-username.github.io`

## 🎨 Image Guidelines

### Profile Photo (`profile.jpg`)
- **Recommended size**: 500x500px (square)
- **Format**: JPG or PNG
- **Tips**: 
  - Use a professional headshot with good lighting
  - Plain or blurred background works best
  - Face should be clearly visible
  - Smile and look approachable!

### Project Screenshots (`project1.jpg`, etc.)
- **Recommended size**: 1200x630px (landscape)
- **Format**: JPG or PNG
- **Tips**:
  - Show the main interface or key features
  - Use high-quality screenshots
  - Crop to show the most interesting parts
  - Consider adding mockups for mobile apps

### Where to Get Images

**Free Stock Photos:**
- [Unsplash](https://unsplash.com) - High-quality free images
- [Pexels](https://pexels.com) - Free stock photos
- [Pixabay](https://pixabay.com) - Free images and videos

**Create Custom Graphics:**
- [Canva](https://canva.com) - Easy graphic design tool
- [Figma](https://figma.com) - Professional design tool
- [Photopea](https://photopea.com) - Free Photoshop alternative

**Screenshot Tools:**
- [Screely](https://screely.com) - Beautiful browser mockups
- [Cleanmock](https://cleanmock.com) - Device mockups
- Windows: Win + Shift + S
- Mac: Cmd + Shift + 4

**AI Image Generators:**
- [DALL-E](https://openai.com/dall-e-2)
- [Midjourney](https://midjourney.com)
- [Stable Diffusion](https://stablediffusionweb.com)

## 🖼️ Repository Structure

```
your-username.github.io/
├── index.html
├── style.css
├── script.js
├── README.md
└── images/
    ├── profile.jpg
    ├── project1.jpg
    ├── project2.jpg
    ├── project3.jpg
    └── project4.jpg
```

## ✏️ Customization Guide

### Update Personal Information

Open `index.html` and replace:

- **Line 11**: `<title>Your Name - Portfolio</title>` → Your name
- **Line 17**: `<a href="#" class="logo">YourName</a>` → Your name
- **Line 29**: `Hi, I'm <span class="highlight">Your Name</span>` → Your name
- **Lines 32-37**: Update your bio description
- **Lines 42-45**: Update social media links
- **Line 51**: Email address

### Update Skills

In `index.html`, find the skills section (around line 65) and modify:

```html
<span class="skill-tag">Your Skill</span>
```

### Update Experience

Find the timeline section (around line 95) and modify each timeline item:

```html
<div class="timeline-item">
    <div class="timeline-dot"></div>
    <div class="timeline-content">
        <h3>Your Job Title</h3>
        <p class="timeline-date">Start - End Date</p>
        <p>Your job description</p>
    </div>
</div>
```

### Update Projects

Find the projects section (around line 140) and modify each project card:

```html
<div class="project-card">
    <div class="project-icon">
        <i class="fas fa-robot"></i> <!-- Change icon -->
    </div>
    <h3>Project Name</h3>
    <p>Project description</p>
    <div class="project-tags">
        <span>Tech1</span>
        <span>Tech2</span>
    </div>
    <a href="your-project-url" class="project-link">View Project <i class="fas fa-arrow-right"></i></a>
</div>
```

### Update Contact Information

Find the contact section (around line 185) and update:

- Email address
- Location
- GitHub username
- Other contact links

### Change Colors

Open `style.css` and modify the CSS variables at the top (around line 11):

```css
:root {
    --primary-color: #6366f1;     /* Main blue color */
    --secondary-color: #8b5cf6;   /* Purple color */
    --accent-color: #ec4899;      /* Pink color */
    /* ... other colors ... */
}
```

## 📱 Features

- **Responsive Design**: Works on all devices (mobile, tablet, desktop)
- **Smooth Animations**: Fade-in effects and smooth scrolling
- **Modern UI**: Gradient effects and glass morphism
- **Interactive Elements**: Hover effects and transitions
- **Contact Form**: Ready for backend integration

## 🎨 Icon Reference

This site uses Font Awesome icons. Find more icons at [fontawesome.com/icons](https://fontawesome.com/icons)

Common icon classes:
- `fa-robot` - Robot icon
- `fa-globe` - Globe icon
- `fa-brain` - Brain icon
- `fa-mobile-alt` - Mobile icon
- `fa-github` - GitHub icon
- `fa-linkedin` - LinkedIn icon
- `fa-twitter` - Twitter icon
- `fa-envelope` - Email icon

## 🔧 Advanced Customization

### Adding a New Section

1. Add the section HTML in `index.html`
2. Add corresponding styles in `style.css`
3. Update navigation links if needed

### Integrating Contact Form

The contact form needs a backend service. Options:

1. **Formspree**: [formspree.io](https://formspree.io)
2. **EmailJS**: [emailjs.com](https://www.emailjs.com)
3. **Netlify Forms**: If you move to Netlify
4. **Your own backend**: Create API endpoint

Example with Formspree:

```html
<form class="contact-form" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
    <!-- form fields -->
</form>
```

## 📝 Tips

1. **Test locally**: Open `index.html` in your browser before uploading
2. **Optimize images**: Compress images before uploading (use [TinyPNG](https://tinypng.com))
3. **Image sizes**: Keep images under 500KB for fast loading
4. **Alt text**: Images already have descriptive alt text for accessibility
5. **Regular commits**: Save your changes frequently
6. **Use branches**: Create branches for major changes
7. **SEO**: Update meta tags in `<head>` for better search visibility

## 🌟 Next Steps

- Add your own profile picture
- Include project screenshots
- Add a blog section
- Implement dark/light mode toggle
- Add more interactive elements
- Connect contact form to backend
- Add Google Analytics

## 📄 License

Free to use for personal and commercial projects.

## 🤝 Contributing

Feel free to fork and customize this template for your own use!

---

Built with ❤️ using HTML, CSS, and JavaScript