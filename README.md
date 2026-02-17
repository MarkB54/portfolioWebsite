# Mark Bastoulis - Portfolio

My personal portfolio website, built with [Astro](https://astro.build), [Tailwind CSS](https://tailwindcss.com), and [DaisyUI](https://daisyui.com).

Based on the [Bloomfolio](https://github.com/lauroguedes/bloomfolio) template by [Lauro Guedes](https://lauroguedes.dev).

## Getting Started

```bash
npm install
npm run dev
```

The site runs at `http://localhost:4321`.

## Commands

| Command | Action |
| :--- | :--- |
| `npm run dev` | Start dev server |
| `npm run build` | Build for production (`./dist/`) |
| `npm run preview` | Preview production build |
| `npm run astro check` | Run type checking |

## Managing Content

Content lives in `src/content/` and can be edited directly or through the Keystatic CMS at `/keystatic`.

### Content Sections

- **Hero** - Name, title, avatar, social links (`src/content/hero/index.yaml`)
- **About** - Bio and photo (`src/content/about/`)
- **Experience** - Employment history (`src/content/work/`)
- **Projects** - Portfolio items (`src/content/projects/`)
- **Education** - Academic background (`src/content/education/`)


## Tech Stack

- [Astro 5](https://astro.build) - Static site generator
- [Tailwind CSS 4](https://tailwindcss.com) - Utility-first CSS
- [DaisyUI 5](https://daisyui.com) - Component library
- [Keystatic](https://keystatic.com) - Git-based CMS
- [TypeScript](https://www.typescriptlang.org/) - Type safety

## Credits

This portfolio is built on the [Bloomfolio](https://github.com/lauroguedes/bloomfolio) template. Thanks to [Lauro Guedes](https://lauroguedes.dev) for creating and open-sourcing it.

## License

MIT
