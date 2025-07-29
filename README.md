# Master's Thesis Proposal Landing Page

A modern, responsive landing page for presenting your Master's thesis proposal on "Evaluating the Efficacy of LLM-Generated UI Modules for Personalized Learning Dashboards."

## 🚀 Features

### Design & Layout
- **Modern Academic Design**: Professional aesthetic with pastel blue theme
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **Interactive Elements**: Smooth animations, hover effects, and transitions
- **Accessibility**: Semantic HTML and keyboard navigation support

### Sections Included
1. **Hero Section**: Title, subtitle, author info, DTU branding, CTA buttons
2. **Executive Summary**: Comprehensive research overview with detailed explanation
3. **Problem Statement**: Clear articulation of the research problem
4. **Research Questions**: Interactive tabs for RQ1, RQ2, and RQ3
5. **Methodology**: Detailed 3-phase approach with module comparison
6. **Timeline**: Visual 6-month research plan with milestones
7. **Company Collaboration**: Partnership details with Digital Ops
8. **Expected Outcomes**: Three key deliverables and broader impact
9. **Contact Section**: Contact info and newsletter signup

### Interactive Features
- **Smooth Scrolling**: Navigation links smoothly scroll to sections
- **Tab System**: Interactive research questions with tab switching
- **Mobile Menu**: Hamburger menu for mobile devices
- **Scroll Progress**: Visual progress indicator at the top
- **Notifications**: Toast notifications for user actions
- **Parallax Effects**: Subtle parallax scrolling in hero section
- **Hover Effects**: Interactive cards and buttons

## 📁 File Structure

```
thesis-landing-page/
├── index.html          # Main HTML structure
├── styles.css          # All CSS styles and responsive design
├── script.js           # JavaScript functionality and interactions
└── README.md           # This documentation file
```

## 🛠️ How to Use

### 1. Basic Setup
1. Download all files to your local directory
2. Open `index.html` in a web browser
3. The page will load with all functionality intact

### 2. Customization

#### Content Updates
- **Author Information**: Update name, supervisor, and institution in the hero section
- **Research Details**: Modify research questions, methodology, and timeline
- **Contact Information**: Update email, LinkedIn, and other contact details
- **Company Information**: Change Digital Ops details to your actual partner

#### Styling Changes
- **Colors**: Modify CSS variables in `styles.css`:
  ```css
  :root {
      --primary-blue: #1e3a8a;
      --secondary-blue: #3b82f6;
      --accent-yellow: #f59e0b;
      --accent-teal: #14b8a6;
  }
  ```
- **Fonts**: Change the Google Fonts import in `index.html`
- **Layout**: Adjust grid layouts and spacing in CSS

#### Functionality Modifications
- **Download Button**: Update the `downloadProposal()` function in `script.js` to link to your actual PDF
- **Newsletter**: Connect the newsletter signup to your backend service
- **Animations**: Modify animation timing and effects in CSS and JavaScript

### 3. Deployment

#### Local Development
- Use a local server (e.g., Python's `http.server` or Node.js `live-server`)
- Test on different devices and browsers

#### Web Hosting
- Upload files to any web hosting service (GitHub Pages, Netlify, Vercel, etc.)
- Ensure all files are in the same directory
- Test all functionality after deployment

## 🎨 Design System

### Color Palette
- **Primary Blue**: `#1e3a8a` - Main brand color
- **Secondary Blue**: `#3b82f6` - Accent and links
- **Accent Yellow**: `#f59e0b` - Highlights and CTAs
- **Accent Teal**: `#14b8a6` - Secondary accents
- **Pastel Blue**: `#e0f2fe` - Hero background
- **Text Dark**: `#1f2937` - Primary text
- **Text Light**: `#6b7280` - Secondary text

### Typography
- **Font Family**: Inter (Google Fonts)
- **Weights**: 300, 400, 500, 600, 700
- **Responsive**: Scales appropriately on all devices

### Components
- **Cards**: Consistent styling with hover effects
- **Buttons**: Primary and secondary button styles
- **Navigation**: Fixed header with smooth transitions
- **Forms**: Clean input styling with validation

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px

## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🚀 Performance Features

- **Optimized CSS**: Efficient selectors and minimal redundancy
- **Lazy Loading**: Images and heavy content load on demand
- **Smooth Animations**: Hardware-accelerated CSS transitions
- **Minimal JavaScript**: Lightweight interactions without heavy frameworks

## 📝 Content Sections

### Executive Summary
Comprehensive overview of the research including:
- Problem statement about static dashboards
- Collaboration with Digital Ops and Strive AI
- Research objectives and expected outcomes

### Research Questions
Three main research questions with detailed sub-points:
- **RQ1**: Usability & Perception
- **RQ2**: Engagement & Behavior  
- **RQ3**: Design & Implementation

### Methodology
Three-phase approach:
- **Phase 1**: Module Design & Implementation
- **Phase 2**: User Study (16-20 participants)
- **Phase 3**: Data Collection & Analysis

### Timeline
6-month research plan with specific milestones:
- Month 1: Onboarding and setup
- Month 2-3: Design and implementation
- Month 4: User study
- Month 5: Data analysis
- Month 6: Finalization

## 📊 Customization Guide

### Adding New Sections
1. Add HTML structure in `index.html`
2. Add corresponding CSS in `styles.css`
3. Add any JavaScript functionality in `script.js`
4. Update navigation menu if needed

### Modifying Animations
- Edit CSS animations in `styles.css`
- Modify JavaScript animation triggers in `script.js`
- Adjust timing and easing functions

### Updating Content
- Replace placeholder text with your actual content
- Update images and icons as needed
- Modify contact information and links

## 🤝 Contributing

Feel free to customize this landing page for your own thesis proposal. The code is well-commented and modular for easy modification.

## 📄 License

This project is open source and available under the MIT License.

## 📞 Support

For questions or customization help, please refer to the code comments or create an issue in the repository.

---

**Built with ❤️ for academic presentations** 