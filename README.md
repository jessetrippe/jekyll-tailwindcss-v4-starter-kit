# Jekyll + TailwindCSS v4 Starter Kit

This is a simple starter kit for using the latest version of **Jekyll** with **TailwindCSS v4**. It provides a modern development workflow, including **live reloading in dev mode** and **minification/purging in build mode**. The setup includes some opinions on content organization but remains flexible enough for customization.

## Features

- **Jekyll** for static site generation
- **TailwindCSS v4** for utility-first styling
- **Live reloading** for development
- **CSS optimization** (minification and purging) for production builds
- Organized directory structure for easy page management

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/jekyll-tailwind-starter.git
   cd jekyll-tailwind-starter
   ```
2. Install dependencies:
   ```sh
   bundle install
   npm install
   ```
3. Run the development server:
   ```sh
   bundle exec jekyll serve --livereload
   ```

## Build for Production

To build the site with optimized TailwindCSS:
```sh
JEKYLL_ENV=production bundle exec jekyll build
```

## File Structure

```
./
├── _config.yml          # Jekyll configuration
├── _layouts/           # Layout files
├── _includes/          # Partial templates
├── _pages/              # Site pages
├── styles/             # TailwindCSS source styles
├── _site/              # Built output (ignored in Git)
├── postcss.config.js   # PostCSS configuration
├── package.json        # Node dependencies
├── Gemfile             # Ruby dependencies
└── README.md           # This file
```

## Customization
- Modify `main.css` to adjust styles and settings.
- Adjust `_config.yml` for Jekyll-specific configurations.
- Add/remove pages under the `pages/` directory as needed.

## Contributions
Contributions are welcome! Feel free to submit issues and pull requests.

## License
This project is licensed under the MIT License.
