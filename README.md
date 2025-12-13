# Huddle Hero Landing Page (Vanilla Web)

A clean, responsive landing page built using vanilla HTML and CSS.

![Huddle Hero Landing Page Preview](./images/active-states.jpg)

## Key Features & Benefits

- **Clean and Simple:** Built using only vanilla HTML and CSS for a lightweight, dependency-free landing page.
- **Responsive Design:** Mobile-first approach with optimized layouts for both mobile and desktop viewports (desktop styles at `992px`).
- **Polished Visuals:** Thoughtful use of CSS custom properties, shadows, and layout to create a modern landing page.
- **Accessible & Semantic:** Uses semantic HTML structure to improve accessibility and SEO.
- **Easy to Integrate:** Drop the `index.html`, `style.css`, and the `images/` folder into any project—no build step required.
- **Customizable:** Clear class names and CSS variables make it simple to change colors, typography, spacing, and copy.

## Prerequisites & Dependencies

- A web browser (Chrome, Firefox, Safari, Edge) to view the landing page.
- A text editor or IDE to edit `index.html` and `style.css` (e.g., VS Code).
- (Optional) A local server for consistent asset loading (VS Code Live Server).

## Installation & Setup Instructions

1. **Clone or download the repository** (or copy the project folder locally):

```bash
git clone https://github.com/yourusername/huddle-hero-landing-vanilla-12.git
```

```bash
cd huddle-hero-landing-vanilla-12
```

2. **Open the project** in your editor and open `index.html` in the browser:

- Double-click `index.html` or open it from your editor.
- Or serve the folder using a simple local server (recommended for consistent image loading)

## Usage Examples

The landing page is a template for Huddle Hero. To customize, edit `index.html`:

- Update the main title in the `.huddle-hero__title` element.
- Change the description in `.huddle-hero__description`.
- Update the CTA button text in `.huddle-hero__cta-button`.
- Edit the social media links in `.huddle-hero__social-buttons` section.

Example: to update the main title, find the `.huddle-hero__title` element and replace the text:

```html
<h1 class="huddle-hero__title center">Build The Community Your Fans Will Love</h1> <!-- Update this text -->
```

## Configuration Options

Most visual settings live in `style.css` using CSS custom properties at the top of the file (`:root`). Common adjustments:

- **Colors & Palette:** Edit variables such as `--MAIN-BG`, `--TITLE-CLR`, `--DESCRIPTION-CLR`, `--BUTTON-BG`, and other `--` variables near the top of `style.css`.
- **Typography:** Change the `--FF1` and `--FF2` font-family or the `@import` Google Font entry to swap fonts.
- **Layout & Spacing:** Modify `.huddle-hero` grid properties, padding, and margins to alter layout proportions.
- **Responsive Breakpoint:** Desktop styles apply at `@media (min-width: 992px)` — change that value if needed.

## Contributing Guidelines

Contributions are welcome. Suggested flow:

1. Fork the repository.
2. Create a feature branch (e.g., `feature/add-new-section`).
3. Make focused commits and push to your fork.
4. Open a pull request describing your changes.

## License

License not specified.

## Acknowledgments

- Google Fonts for the `Poppins` and `Open Sans` fonts used in this project.