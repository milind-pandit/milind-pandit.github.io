# Milind Pandit — Personal Website

Source for my academic website: **https://milind-pandit.github.io/**

I am an R&D Engineer at IMEC (Leuven, Belgium) working on micromachined ultrasound transducers (pMUT/cMUT) and MEMS sensors and actuators for health and wearable applications. The site contains my biography, publications, experience, and downloadable academic and industry CVs.

## Structure

| Path | Contents |
| :--- | :--- |
| `data/authors/me.yaml` | Profile: bio, education, experience, skills, languages, awards, links |
| `content/_index.md` | Homepage |
| `content/experience.md` | Experience page |
| `content/publications/` | One folder per publication |
| `static/uploads/` | Downloadable CVs |
| `assets/css/custom.css` | Layout and styling adjustments |
| `layouts/` | Overrides of individual page blocks |

The site is built with [Hugo](https://gohugo.io/) and deployed to GitHub Pages automatically by GitHub Actions on every push to `main`.

To preview locally (requires Hugo extended and Node.js):

```bash
pnpm install
hugo server
```

## License

**Content** — all text, CVs, images and other material describing me and my work (including everything in `content/`, `data/`, `static/` and `assets/media/`) is © Milind Pandit and licensed under [Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International (CC BY-NC-ND 4.0)](https://creativecommons.org/licenses/by-nc-nd/4.0/). You may share it with attribution, but not use it commercially or distribute modified versions.

**Code** — the site is built on the open-source [HugoBlox](https://github.com/HugoBlox/kit) framework, whose code is used under the MIT License; see [`LICENSE.md`](LICENSE.md). The MIT License applies only to that code, not to the content above.
