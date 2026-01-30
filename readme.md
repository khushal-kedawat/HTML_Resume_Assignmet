# Portfolio Website - Khushal Kedawat

A simple, clean static HTML portfolio website showcasing professional experience, skills, projects, and education.

## 📋 Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Customization Guide](#customization-guide)
- [Browser Compatibility](#browser-compatibility)
- [Evaluation Checklist](#evaluation-checklist)

## 🎯 Overview

This is a single-page portfolio website built with pure HTML and CSS. It presents professional information in a structured, easy-to-read format without requiring any frameworks or dependencies.

## ✨ Features

- **Responsive Design**: Mobile-friendly viewport meta tag included
- **Clean Layout**: Organized sections with clear hierarchy
- **Semantic HTML**: Proper use of headings, lists, and tables
- **Professional Sections**:
  - About Me
  - Technical Skills
  - Work Experience (tabular format)
  - Project Showcase
  - Education History
  - Contact Information

## 🚀 Setup Instructions

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- A text editor (VS Code, Sublime Text, Notepad++, etc.) - optional for customization

### Installation Steps

1. **Save the HTML file**
   - Copy the HTML code and save it as `index.html` or `portfolio.html`
   - Ensure the file has a `.html` extension

2. **Organize your files** (recommended structure)
   ```
   portfolio/
   ├── index.html
   └── README.md
   ```

3. **No dependencies required**
   - This is a standalone HTML file with inline CSS
   - No installation of packages or frameworks needed

## 💻 Usage

### Method 1: Direct Browser Opening
1. Locate the HTML file on your computer
2. Right-click on the file
3. Select "Open with" → Choose your preferred browser
4. The portfolio will display immediately

### Method 2: File Path in Browser
1. Open your web browser
2. Press `Ctrl+O` (Windows/Linux) or `Cmd+O` (Mac)
3. Navigate to and select the HTML file
4. Click "Open"

### Method 3: Live Server (for development)
If you're using VS Code:
1. Install the "Live Server" extension
2. Right-click on the HTML file
3. Select "Open with Live Server"
4. The page will open with auto-reload on save

### Method 4: Deploy Online
You can host this file for free on:
- **GitHub Pages**: Push to a repository and enable GitHub Pages
- **Netlify**: Drag and drop the HTML file
- **Vercel**: Deploy directly from your file system
- **Surge.sh**: Use command line to deploy

## 📁 File Structure

```
Current Structure:
- Single HTML file with inline CSS

Content Sections:
1. Header (Name and Title)
2. About Me
3. Skills (Unordered List)
4. Experience (Table)
5. Projects (Multiple project entries)
6. Education (Table)
7. Contact Information
8. Footer
```

## 🎨 Customization Guide

### Updating Personal Information

1. **Name and Title**
   ```html
   <h1>Your Name</h1>
   <p>Your Title | Your Role | Your Passion</p>
   ```

2. **Skills**
   - Add/remove `<li>` items in the Skills section
   ```html
   <li>Your New Skill</li>
   ```

3. **Experience**
   - Add new table rows in the Experience table
   ```html
   <tr>
     <td>Position</td>
     <td>Company</td>
     <td>Duration</td>
   </tr>
   ```

4. **Projects**
   - Copy and paste a project block, then modify
   ```html
   <h4>Project Name</h4>
   <p>Description...</p>
   <ul>
     <li>Technologies: List here</li>
     <li>Timeline: Duration</li>
   </ul>
   ```

5. **Contact Details**
   - Update email, phone, and location in the Contact section

### Styling Modifications

The current CSS is minimal. To enhance styling:

```css
/* Example: Add colors */
body {
  font-family: Arial, sans-serif;
  max-width: 800px;
  margin: 0 auto;
  padding: 20px;
  line-height: 1.6;
}

h1 {
  color: #2c3e50;
}

h2 {
  color: #34495e;
  border-bottom: 2px solid #3498db;
  padding-bottom: 5px;
}
```

## 🌐 Browser Compatibility

This portfolio works on:
- ✅ Chrome (all versions)
- ✅ Firefox (all versions)
- ✅ Safari (all versions)
- ✅ Edge (all versions)
- ✅ Opera (all versions)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## ✅ Evaluation Checklist

Use this checklist to evaluate the portfolio:

### Content Quality
- [ ] All personal information is present and accurate
- [ ] Skills are relevant and up-to-date
- [ ] Experience entries include position, company, and duration
- [ ] Projects have clear descriptions and technology lists
- [ ] Education details are complete
- [ ] Contact information is functional

### Technical Implementation
- [ ] HTML is valid and semantic
- [ ] Tables are properly structured with headers
- [ ] Lists use appropriate tags (ul/ol)
- [ ] Page has a proper title
- [ ] Viewport meta tag is included for mobile responsiveness
- [ ] All sections are separated with horizontal rules

### Presentation
- [ ] Text is readable and well-formatted
- [ ] Tables have borders for clarity
- [ ] Hierarchy is clear (h1 > h2 > h4)
- [ ] Information flows logically from top to bottom

### Functionality
- [ ] Page loads without errors
- [ ] All text displays correctly
- [ ] Tables render properly
- [ ] Footer includes copyright notice

## 📝 Notes

- **Typos to fix**: "experince" → "experience", "Techonoliges" → "Technologies", "pythone" → "python"
- **Enhancement suggestions**: Consider adding links to projects, social media profiles, or downloadable resume
- **Accessibility**: Consider adding alt text for any future images and ARIA labels for better screen reader support

## 🤝 Contributing

To improve this portfolio:
1. Make your changes to the HTML file
2. Test in multiple browsers
3. Validate HTML at [W3C Validator](https://validator.w3.org/)
4. Document any new features in this README

## 📄 License

© 2026 Khushal Kedawat. All rights reserved.

---

**Last Updated**: January 2026  
**Version**: 1.0.0