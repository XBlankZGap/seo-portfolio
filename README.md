# SEO Analytics - Hugo Static Site

This is a static site version of the SEO Analytics dashboard, built with the Hugo framework and styled with Tailwind CSS.

## Prerequisites

- [Hugo](https://gohugo.io/installation/) (Extended version recommended)
- [Tailwind CSS](https://tailwindcss.com/docs/installation) (Handled via CDN in this version for simplicity)

## How to Run Locally

1.  **Install Hugo**: Ensure you have Hugo installed on your machine.
2.  **Clone the repository**: (If applicable)
3.  **Navigate to the project directory**:
    ```bash
    cd hugo
    ```
4.  **Start the Hugo server**:
    ```bash
    hugo server -D
    ```
5.  **View the site**: Open your browser and navigate to `http://localhost:1313`.

## Project Structure

- `hugo.toml`: Main configuration file.
- `content/`: Markdown files for each page.
- `layouts/`: HTML templates for the site structure and individual pages.
  - `_default/`: Base templates (`baseof.html`, `single.html`, `list.html`).
  - `partials/`: Reusable HTML components (`header.html`, `sidebar.html`, `footer.html`).
  - `index.html`: Homepage layout.
  - `{section}/`: Specific layouts for each section of the dashboard.
- `static/`: Static assets like images, fonts, etc. (Currently using CDNs and external URLs).

## Customization

- **Styling**: Tailwind CSS is configured in `layouts/_default/baseof.html`. You can modify the `tailwind.config` object there.
- **Navigation**: The main menu is defined in `hugo.toml`.
- **Content**: Edit the `.md` files in the `content/` directory to update text and metadata.
- **Layouts**: Modify the `.html` files in the `layouts/` directory to change the structure and design.

## Deployment

To build the static site for production:

```bash
hugo
```

This will generate a `public/` directory containing the final HTML, CSS, and JS files, which can be hosted on any static web hosting service (e.g., Netlify, Vercel, GitHub Pages).
