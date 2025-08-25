# Personal CV Website

A beautiful, responsive personal CV website designed for AI researchers and computer scientists.

## 🖼️ Adding Images

### Profile Photo
1. Add your profile photo to the `images/` folder (recommended: `profile.jpg`)
2. In `index.html`, uncomment line 53 and update the src path:
   ```html
   <img src="images/profile.jpg" alt="Your Name" class="profile-image">
   ```
3. Comment out or remove the placeholder div (lines 54-57)

### Project Images
Replace the project placeholders with actual screenshots:

1. **NeuroVision Project**: Add `images/neurovision-project.jpg`
   - Uncomment line 237 in `index.html`
   - Comment out the placeholder (lines 238-241)

2. **BayesianCV Project**: Add `images/bayesian-cv-project.jpg`
   - Uncomment line 265 in `index.html`
   - Comment out the placeholder (lines 266-269)

3. **VariationalNet Project**: Add `images/variational-net-project.jpg`
   - Uncomment line 293 in `index.html`
   - Comment out the placeholder (lines 294-297)

## 🎨 Color Palette

The website uses an extended warm color palette:

### Primary Colors
- **Cream**: `#f4ebe4` - Main background
- **Sage**: `#d4d0b8` - Accent elements
- **Dusty Rose**: `#d4b5a0` - Secondary color
- **Terracotta**: `#c8756d` - Primary action color

### Extended Palette
- **Warm Beige**: `#f0e6d2`
- **Soft Olive**: `#c4c2a0`
- **Muted Coral**: `#e0a390`
- **Deep Terracotta**: `#b86b5f`
- **Sage Light**: `#e2dfc8`
- **Dusty Mauve**: `#c9a696`
- **Warm Taupe**: `#a69080`
- **Soft Peach**: `#f2d5c4`

### Accent Colors
- **Accent Blue**: `#8db4d3`
- **Accent Green**: `#a8c4a2`
- **Accent Purple**: `#b8a8c8`
- **Accent Gold**: `#d4b896`

## 📝 Customizing Content

### Personal Information
Update the following in `index.html`:
- Name in `<title>` and `<h1>` tags
- Job title and description
- Contact information in the contact section
- Social media links

### Experience & Education
- Update timeline items in the education section
- Modify experience cards with your actual work history
- Add or remove education entries as needed

### Projects
- Update project titles, descriptions, and tech stacks
- Modify GitHub and demo links
- Add more project cards by copying the existing structure

## 🚀 Features

- **Responsive Design**: Works on desktop, tablet, and mobile
- **Modern Animations**: Smooth scrolling, hover effects, and entrance animations
- **Accessible**: Keyboard navigation and screen reader friendly
- **Fast Loading**: Optimized CSS and JavaScript
- **SEO Ready**: Semantic HTML structure

## 📱 Mobile Navigation

The website includes a hamburger menu for mobile devices with smooth animations and touch-friendly interactions.

## 🎯 Performance

- Uses CSS custom properties for easy theme customization
- Debounced scroll events for smooth performance
- Intersection Observer for efficient animations
- Minimal JavaScript dependencies (only Font Awesome icons)

## 🔧 Technical Stack

- **HTML5**: Semantic structure
- **CSS3**: Grid, Flexbox, Custom Properties, Animations
- **Vanilla JavaScript**: No frameworks, pure performance
- **Font Awesome**: Icon library
- **Google Fonts**: Inter font family

---

**Note**: This website is designed to showcase AI and computer science expertise. All dummy content relates to neuromorphic computing, probabilistic inference, and computer vision to match your research interests.
