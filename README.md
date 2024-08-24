# Purple Theme

**Version:** 1.0  
**Author:** Sanjay Sharma  
**License:** LGPL-3  

## Description
The Purple Theme is a custom, creative theme designed for Odoo websites. It offers a visually appealing purple-centric design, perfect for businesses looking for a modern and stylish online presence. This theme provides customized snippets, layouts, and design elements that can be easily integrated into your Odoo website.

## Key Features
- Custom-designed header and footer templates
- Stylish banner snippet for homepage customization
- Easy integration with Odoo’s website module
- Includes font and SCSS assets for a seamless experience
- Preconfigured assets for primary variables and frontend customization

## Installation
To install the theme, follow these steps:
1. Download the module and place it in your Odoo add-ons directory.
2. Update your app list in Odoo.
3. Install the “Purple Theme” from the website module.

## Dependencies
This theme depends on the following Odoo module:
- `website`

## Configuration
The theme includes customizable snippets and assets:
- **Snippets:**
  - `s_banner`: A customizable banner snippet for the homepage.
- **Assets:**
  - `web._assets_primary_variables`: Includes SCSS variables for the theme’s primary colors and styles.
  - `web.assets_frontend`: Includes fonts and SCSS for typography.

## Files Included
### Data Files:
- `views/snippets/s_banner.xml`: Configuration for the banner snippet.
- `views/footer.xml`: Footer template.
- `views/header.xml`: Header template.

### Image Assets:
- `static/description/theme_description.jpg`: Theme overview image.
- `static/description/theme_purple.jpg`: Preview image for the theme.
- `static/src/img/background/img1.jpg`: Default background image for the banner.

### SCSS and Font Assets:
- `theme_purple/static/src/scss/primary_variables.scss`: SCSS for primary variables.
- `theme_purple/static/fonts/*`: Custom fonts used in the theme.
- `theme_purple/static/src/scss/font.scss`: SCSS configuration for fonts.

## Usage
1. After installing the theme, navigate to the website editor.
2. Select the banner snippet from the homepage configurator.
3. Customize the header, footer, and other elements as needed using Odoo’s drag-and-drop builder.

## License
This theme is licensed under LGPL-3. See the LICENSE file for details.
