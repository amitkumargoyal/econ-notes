# econ-notes

Microeconomics teaching notes — full derivations, exercises, and reproducible figures. A companion to the [Econschool](https://econschool.in) videos and the [@econ.school](https://www.youtube.com/@econ.school) YouTube channel.

**Read the notes:** <https://amitkumargoyal.github.io/econ-notes/>

## Audience

Students preparing for postgraduate study in economics (DSE, ISI, and international MA/PhD programmes). The emphasis is on full mathematical working.

## Build

Built with [Quarto](https://quarto.org), Python ([uv](https://docs.astral.sh/uv/)-managed), and [MathJax](https://www.mathjax.org/). Figures are generated from Python code at build time, so they're reproducible and adaptable. Deployed to GitHub Pages via GitHub Actions on every push to `main`.

Local development:

```bash
git clone https://github.com/amitkumargoyal/econ-notes.git
cd econ-notes
uv sync
quarto preview
```

## Author

[Amit Goyal](https://econschool.in) · <amit@econschool.in>

## Licence

To be added.