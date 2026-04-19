# alex-anast.com

Personal portfolio website for Alexandros Anastasiou -- AI & Software Engineer.

**Live at:** [alex-anast.com](https://alex-anast.com)

## Tech Stack

- [Hugo](https://gohugo.io/) (Extended) -- static site generator
- [hugo-noir](https://github.com/prxshetty/hugo-noir) theme (git submodule)
- [Tailwind CSS](https://tailwindcss.com/) (CDN) + [Devicon](https://devicon.dev/) icons
- Deployed via GitHub Actions to GitHub Pages

## Project Structure

```
content/            Markdown pages (about, blog, cv, certifications, contact, etc.)
data/en/            Structured TOML data (author, experience, education, projects, certifications)
layouts/            Custom Hugo templates overriding the theme
static/assets/      Images, documents (resume PDF)
themes/hugo-noir/   Theme submodule
.github/workflows/  CI/CD pipeline
hugo.toml           Site configuration
```

## Local Development

```bash
# Clone with submodules
git clone --recurse-submodules https://github.com/alex-anast/alex-anast.github.io.git
cd alex-anast.github.io

# Start dev server
hugo server
```

Requires [Hugo Extended](https://gohugo.io/installation/) v0.123+.

## Deployment

Pushes to `master` trigger the GitHub Actions workflow (`.github/workflows/hugo.yml`), which builds with `hugo --minify` and deploys to GitHub Pages.

## License

Content and design are personal. The [hugo-noir](https://github.com/prxshetty/hugo-noir) theme has its own license.
