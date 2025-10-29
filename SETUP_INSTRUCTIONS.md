# Portfolio Site Structure - Setup Instructions

## Current Setup

Your portfolio website now has a **separate Under Development page** that displays while your main portfolio is being worked on.

### File Structure:
```
d:/my/portfolio/
├── index.html                    ← CURRENTLY DISPLAYS "Coming Soon" page
├── coming-soon.html              ← Alternative name (same as index.html)
├── portfolio.html                ← Your full portfolio (hidden for now)
├── css/
│   ├── styles.css               (Portfolio CSS)
│   └── development.css          (Under Development CSS)
├── js/
│   ├── script.js                (Portfolio JS)
│   └── development.js           (Under Development JS)
└── pages/
    └── under-development.html    (Backup copy)
```

## How to Switch Between Pages

### **DISPLAY "Coming Soon" Page (Current)**
The `index.html` currently displays the "Under Development" page. This is what visitors see when they go to `shankongahage.live`

### **DISPLAY Full Portfolio**
When you're ready to show your portfolio:
1. Replace the current `index.html` with `portfolio.html`
2. OR rename `portfolio.html` to `index.html` and rename the current one

### **QUICK SWITCH STEPS:**

#### To show portfolio instead of coming soon:
```
1. Delete current index.html (or backup it)
2. Move portfolio.html content to index.html
3. Update CSS link to: css/styles.css
4. Update JS link to: js/script.js
```

#### To go back to coming soon:
```
1. Restore index.html from coming-soon.html
2. Update CSS link to: css/development.css
3. Update JS link to: js/development.js
```

## Features of Coming Soon Page

✅ **Hero Section** - Attention-grabbing landing  
✅ **Development Progress** - Visual progress bars  
✅ **Timeline** - 4-phase development roadmap  
✅ **Feature Showcase** - 6 upcoming features  
✅ **Email Signup** - Notify me when ready  
✅ **Contact Section** - Direct contact buttons  
✅ **Fully Responsive** - Works on all devices  
✅ **Smooth Animations** - Professional feel  

## Features of Portfolio Page

✅ **Navigation** - Fixed navbar with smooth scrolling  
✅ **About Section** - Your profile and skills  
✅ **Projects** - 3 featured projects  
✅ **Contact Form** - Get in touch  
✅ **Animations** - Scroll-triggered effects  
✅ **Fully Responsive** - Mobile-friendly  

## Contact Information

- **Email:** hello@shankongahage.live
- **Domain:** shankongahage.live
- **Name:** Shan Kongahage

## Customization Tips

### Coming Soon Page:
- Update progress percentages in `pages/under-development.html`
- Modify timeline dates and phases
- Add/change feature descriptions
- Update social media links in footer

### Portfolio Page:
- Update project descriptions and links
- Add real skills in the skills section
- Link real GitHub/LinkedIn profiles
- Customize "About Me" section

## Next Steps

1. **While building:** Keep index.html as coming soon
2. **When ready:** Switch to portfolio.html
3. **Domain:** Configure your domain to point to `shankongahage.live`
4. **Social Links:** Update footer links with real profiles

---

**Built with:** HTML, CSS, JavaScript (Pure vanilla, no frameworks)
**Domain:** shankongahage.live
**Date:** October 29, 2025
