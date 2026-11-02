# Tyrone Adams — CV site

The source for my personal CV website. I’m an Automation Engineer and QA Specialist based in Cape Town, open to roles in the Netherlands, the UK and Australia.

**Live site:** 

## About the site

It’s a single, self-contained `index.html` with no build step, framework or dependencies beyond Google Fonts.

- **Hero test runner:** the page opens with a mock `dotnet test` run whose checks tick over to passing. It respects `prefers-reduced-motion` and shows the passed state immediately when motion is reduced.
- **Light and dark mode:** colours are CSS custom properties that follow the visitor’s system setting.
- **Responsive:** the two-column layout collapses to one column on phones, with safe-area padding for notched screens.
- **Accessible:** it uses semantic HTML, visible focus styles, and an accessible label on the animated runner.

## Sections

About, Experience, Projects (ReviewDock, Testbench, AI review skills), How I test from a diagram, Toolkit, Education and Availability.

## Run it locally

Open `index.html` in any browser. No server is needed.

## Deploy with GitHub Pages

1. Create a public repository named `Tyron3.github.io`.
2. Upload `index.html` and this `README.md` to the root of the `main` branch.
3. In **Settings → Pages**, set the source to **Deploy from a branch**, choose `main` and `/ (root)`, then save.
4. The site goes live at https://tyron3.github.io within a minute or two.

To update the site, edit `index.html` and commit. GitHub Pages redeploys automatically.

## Contact

- Email: [tyr.adams47@gmail.com](mailto:tyr.adams47@gmail.com)
- LinkedIn: [linkedin.com/in/tyroneadams89](https://www.linkedin.com/in/tyroneadams89/)
- GitHub: [github.com/Tyron3](https://github.com/Tyron3)
