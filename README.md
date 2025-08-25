# Penn Engineering Coming Soon Page

A beautiful, customizable "Coming Soon" page template for Penn Engineering courses and projects, featuring official branding and hosted assets.

![Screenshot of the unconfigured "Coming Soon" page](https://raw.githubusercontent.com/jlumbroso/penn-engineering-coming-soon/refs/heads/main/screenshot.png)

## 🚀 Quick Start

1. **Deploy to GitHub Pages**: Simply push this repository to GitHub and enable GitHub Pages in Settings → Pages → Source: Deploy from branch (main)
2. **Customize**: Edit the CSS variables in `index.html` to personalize your page
3. **Done!** Your Coming Soon page is live

## 🎨 Customization Guide

All customization is done through CSS variables at the top of `index.html`. Open the file and look for the `CUSTOMIZATION SECTION` (around line 15).

### Content Controls

#### Display Modes
Control which sections appear on your page by setting these to `'block'` (show) or `'none'` (hide):

```css
--show-tagline: block;        /* Show/hide the tagline */
--show-description: block;    /* Show/hide the description paragraph */
--show-timeline: block;       /* Show/hide the timeline */
--show-contact: block;        /* Show/hide contact information */
```

#### Content Customization
Replace the default text with your own:

```css
--course-name: "Course Title";
--course-code: "ENGR XXX";
--tagline: "Expanding the frontiers of knowledge";
--description: "This course explores fundamental concepts...";
--timeline: "Spring 2025";
--contact-email: "instructor@seas.upenn.edu";
--contact-name: "Dr. Name";
```

### Visual Customization

#### Background Visual
Choose from available Penn Engineering visuals:

```css
--background-visual: url('https://jlumbroso.github.io/penn-engineering-web-assets/visuals/blue/spark-of-ingenuity.png');
```

Available options include:
- `spark-of-ingenuity.png` (default) - The signature Penn Engineering spark
- `circuit.png` - Circuit board pattern
- `laptop.png` - Modern laptop illustration
- `molecules.png` - Molecular structures
- `robotic-arm.png` - Robotics illustration
- `wind-turbine.png` - Sustainable energy
- `eniac.png` - Historic ENIAC computer
- `dna-flask.png` - Bioengineering theme
- `drone.png` - Aerospace engineering
- And many more...

Full list available at: https://jlumbroso.github.io/penn-engineering-web-assets/

#### Visual Settings

```css
--visual-opacity: 0.05;       /* Background image opacity (0-1) */
--animation-enabled: 1;        /* 1 for animations on, 0 for off */
```

## 📋 Configuration Examples

### Example 1: Minimal "Coming Soon"
Just the essentials - perfect for a placeholder:

```css
--show-tagline: none;
--show-description: none;
--show-timeline: none;
--show-contact: none;
--course-name: "Advanced Robotics";
--course-code: "MEAM 520";
```

### Example 2: Coming Soon with Timeline
Include when the course will be available:

```css
--show-tagline: none;
--show-description: none;
--show-timeline: block;
--show-contact: block;
--course-name: "Machine Learning for Engineers";
--course-code: "CIS 519";
--timeline: "Fall 2025";
--contact-email: "ml-course@seas.upenn.edu";
--contact-name: "Prof. Smith";
```

### Example 3: Full Information
Complete details for students:

```css
--show-tagline: block;
--show-description: block;
--show-timeline: block;
--show-contact: block;
--course-name: "Bioengineering Principles";
--course-code: "BE 200";
--tagline: "Where engineering meets medicine";
--description: "This foundational course introduces students to the principles of bioengineering, covering biomechanics, biomaterials, and biomedical instrumentation. Prerequisites: MATH 114, PHYS 150. The course website will be available two weeks before the semester begins.";
--timeline: "Spring 2025 • Registration opens December 1st";
--contact-email: "be200@seas.upenn.edu";
--contact-name: "Dr. Jennifer Chen";
--background-visual: url('https://jlumbroso.github.io/penn-engineering-web-assets/visuals/blue/dna-flask.png');
```

## 🎯 Features

- **Responsive Design**: Looks great on all devices (desktop, tablet, mobile)
- **Animated Elements**: Smooth fade-in animations (can be disabled)
- **Accessibility**: Supports reduced motion preferences
- **Print-Friendly**: Clean output when printed
- **Fast Loading**: Uses CDN-hosted assets
- **No Build Process**: Just HTML - edit and deploy
- **Brand Compliant**: Uses official Penn Engineering colors, fonts, and visuals

## 🏗️ Technical Details

### Fonts Used
- **TWK Everett**: Headlines and body text (Penn Engineering primary font)
- **Pitch Sans**: Technical details and metadata (Penn Engineering secondary font)

### Color Palette
- Penn Blue (`#011F5B`): Primary text
- Penn Red (`#990000`): Accents and emphasis  
- Electric Blue (`#63C7FF`): Interactive elements
- Dark Gray (`#2D2926`): Body text
- Light backgrounds for readability

### Browser Support
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📝 Notes

- All Penn Engineering assets (fonts, logos, visuals) are hosted on GitHub Pages and referenced via HTTPS URLs
- No local assets needed - everything loads from the CDN
- The page is designed to be a template - fork it and customize for your needs
- Animations automatically disable for users who prefer reduced motion

## 🔗 Resources

- **Penn Engineering Web Assets**: https://jlumbroso.github.io/penn-engineering-web-assets/
- **Brand Guidelines**: See `penn-engineering-web-assets/docs/` folder
- **Asset Manual**: `penn-engineering-web-assets/PENN-ENGINEERING-WEB-ASSETS-MANUAL.md`

## 📧 Support

For questions about:
- **This template**: Create an issue in this repository
- **Penn Engineering branding**: marcomms@seas.upenn.edu
- **Technical support**: lumbroso@seas.upenn.edu

## 📄 License

This template is provided for use by Penn Engineering faculty, staff, and students for official university purposes.

---

*Last Updated: January 2025*
