# Netflix UI Clone 🎬

A responsive Netflix-inspired user interface built with HTML, CSS, and semantic web standards.

## Features ✨

- **Fixed Navigation Bar** - Netflix branding with responsive nav links
- **Hero Section** - Movie showcase with title, description, and action buttons
- **Trending Carousel** - Horizontal scrolling movie poster gallery
- **Responsive Design** - Mobile, tablet, and desktop friendly
- **Semantic HTML** - Clean, accessible markup with proper structure
- **BEM CSS Naming** - Organized and maintainable stylesheets
- **Sticky Content** - Hero section stays in place during scroll
- **Modern Styling** - Dark theme with Netflix red accents

## Tech Stack 🛠️

- **HTML5** - Semantic markup with proper structure
- **CSS3** - Flexbox, Grid, Media Queries
- **No frameworks** - Vanilla HTML & CSS

## Project Structure 📁

```
Netflix-Clone-UI/
├── Projects/
│   ├── netflix_clone_UI.html    # Main HTML file
│   ├── netflix_clone_UI.css     # Stylesheet
│   └── ...
├── Images/
│   ├── titanic.jpg              # Hero background
│   └── movies images/           # Poster collection
├── Phase 1 - HTML/              # HTML learning files
├── Phase 2 - CSS/               # CSS learning files
└── README.md                     # This file
```

## CSS Classes (BEM Methodology)

### Navbar

- `.navbar` - Main navigation container
- `.logo` - Logo wrapper
- `.logo__title` - Netflix title
- `.nav-links` - Navigation links list

### Hero Section

- `.hero` - Hero container
- `.hero__content` - Hero content area
- `.hero__actions` - Button container
- `.btn` - Base button style
- `.btn--play` - Play button variant
- `.btn--info` - Info button variant

### Trending Section

- `.trending` - Trending container
- `.trending__title` - Section heading
- `.trending__carousel` - Scrollable wrapper
- `.trending__list` - Movie list
- `.trending__item` - Individual movie item
- `.trending__poster` - Movie poster image

## Responsive Breakpoints 📱

- **Desktop** (1200px+) - Full layout with 2-column grid
- **Tablet** (768px - 1199px) - Single column, centered content
- **Mobile** (480px - 767px) - Optimized for small screens
- **Small Mobile** (<480px) - Minimal spacing, stacked layout

## How to Use 🚀

1. Clone the repository:

```bash
git clone https://github.com/Ahesanali20/netflix-clone-ui.git
```

2. Navigate to the project:

```bash
cd netflix-clone-ui
```

3. Open `Projects/netflix_clone_UI.html` in your browser

4. Customize:
   - Update movie titles and descriptions in HTML
   - Modify colors in CSS variables
   - Add your own movie images to `Images/`

## Key Features Explained 🎯

### Fixed Navbar

The navbar stays at the top while scrolling, featuring the Netflix logo and navigation links.

### Sticky Hero Content

The Titanic hero section moves vertically with the page but stays anchored horizontally for a smooth reading experience.

### Scrollable Carousel

Movie posters are displayed in a horizontal scrollable carousel with fixed width and height.

### Mobile Responsive

The layout adapts gracefully from desktop 2-column grid to single column on mobile devices.

## Customization Guide 🎨

### Change Colors

Update the background colors in CSS:

- `.navbar` - Navigation background
- `.btn--play` - Play button color
- `.logo__title` - Netflix title color

### Update Content

Edit the HTML to:

- Change the movie title (`<h1>`)
- Update the description (`<p>`)
- Replace movie poster images

### Adjust Sizing

Modify these values in CSS:

- `.logo__title` font-size for logo
- `.trending__poster` width/height for poster size
- `.hero__content` max-width for content width

## Browser Support 🌐

- Chrome/Edge (Latest)
- Firefox (Latest)
- Safari (Latest)
- Mobile browsers

## Future Enhancements 🚀

- [ ] Add hamburger menu for mobile
- [ ] Implement smooth scroll animations
- [ ] Add keyboard navigation
- [ ] Create interactive movie details modal
- [ ] Add search functionality
- [ ] Include video player integration

## Learning Resources 📚

This project demonstrates:

- Semantic HTML5 structure
- CSS Flexbox and Grid
- CSS positioning (sticky, fixed)
- Media queries for responsive design
- BEM naming convention
- Accessibility best practices

## License 📄

This project is open source and available under the MIT License.

## Author 👨‍💻

**Ahesanali20** - Frontend Developer

---

**Made with ❤️ for learning web development**

Feel free to fork, modify, and use this project as a learning resource!
