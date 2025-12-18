# fd_styleguide
This is the style guide of Raúl Delicado and Ernesto Garcés
## Emails
- Ernesto Garcés Giner – fhs54939@fh-salzburg.ac.at
- Raúl Delicado – fhs54941@fh-salzburg.ac.at

# Explanation of CSS Formatting Rules 

### Design Tokens
All fundamental values (colors, spacing, typography, shadows, radii) are defined as CSS custom properties inside :root. This ensures consistency across the entire project and allows easy theme adjustments. Example: --color-blue-60, --space-m, --line-height-lg.

### Color System
Colors are organized into scales (Blue, Neutral, Orange) with numeric steps from 10 to 100. Semantic tokens (e.g., --color-text-primary, --color-status-error) map these scales to meaningful usage contexts.

### Typography
Font families, weights, line heights, and letter spacing are standardized. Utility classes like .text--bold, .heading--light follow an OOCSS approach, allowing reuse across components.

### Spacing and Layout
Spacing tokens (--space-xs to --space-xl) are applied consistently for padding, margins, and gaps. Flexbox is used for layout (.body, .main-basic, .section), ensuring responsive alignment.

### Components
Buttons, inputs, forms, and navigation elements are styled with modular classes (.button-primary, .button-error, .button-unactive). Hover, focus, and active states are defined with transitions (--transition-base, --transition-fast) for smooth interactions.

### Responsive Design
Media queries target breakpoints (max-width: 48em) to adjust typography, layout, and button sizes for mobile devices.

### OOCSS Philosophy
Classes are written as reusable objects (.heading--bold, .text--italic) rather than tied to specific components. This makes the style guide scalable and maintainable.