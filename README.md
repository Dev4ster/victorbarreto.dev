# VictorBarreto.dev - Personal Website

This repository contains my personal website, built with [Hugo](https://gohugo.io/) and using the Enchanted Lowkey theme (based on [Lowkey Hugo Theme](https://github.com/nixentric/Lowkey-Hugo-Theme)).

## Features

- Multilingual site (English and Portuguese)
- Blog with categories and tags
- Responsive and minimalist design
- Dark/light mode
- SEO optimized

## Running Locally

```bash
# Install dependencies
npm install

# Start the development server
hugo server -D
```

The website will be available at `http://localhost:1313/`.

## Project Structure

```
.
├── assets/             # Resources processed by Hugo Pipes
├── config/             # Hugo configurations
│   └── _default/       # Default configurations
│       ├── hugo.toml   # Main configuration
│       ├── menus.toml  # Site menus
│       └── params.toml # Custom parameters
├── content/            # English content
│   ├── posts/          # Blog articles in English
│   └── about.md        # "About" page in English
├── content/br/         # Portuguese content
│   ├── posts/          # Blog articles in Portuguese
│   └── about.md        # "About" page in Portuguese
├── i18n/               # Translation files
│   ├── en.toml         # English translations
│   └── pt-br.toml      # Portuguese translations
├── layouts/            # Custom templates
├── static/             # Static files (images, etc)
└── themes/             # Enchanted Lowkey theme
```

## Theme Customization

The Enchanted Lowkey theme has been customized to add:

- Support for multiple languages
- Automatic language selector
- Dark/light mode toggle
- Accessibility improvements
- Tailwind CSS integration

## Internationalization

The site supports English and Brazilian Portuguese. Translation files are in `i18n/` and Portuguese content is in `content/br/`.

URL for Portuguese content follows the pattern `/pt-br/` (e.g., `/pt-br/about/`).

## Deployment

The site is automatically deployed to Cloudflare Pages on every push to the main branch.

## Special Front Matter Parameters

In addition to standard Hugo parameters, the site uses some custom parameters:

- `hideReadingTime: true` - Disables the display of estimated reading time
- `tableOfContents: true` - Enables the table of contents for the post
- `description: ""` - Custom description for SEO and metadata

## License

Copyright © 2025 Victor Barreto. All rights reserved.

## Contact

For more information, please contact me at [hi@victorbarreto.dev](mailto:hi@victorbarreto.dev). 