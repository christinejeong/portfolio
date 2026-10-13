<div align="center">

# Christine Jeong

### Engineering ideas with an artist’s eye.

A personal portfolio of software, AI, and product design—built around thoughtful experiences and the work behind them.

[**Explore the portfolio ↗**](https://christinejeong.github.io/Portfolio/portfolio.html) · [Projects](https://christinejeong.github.io/Portfolio/portfolio.html#projects) · [About me](https://christinejeong.github.io/Portfolio/portfolio.html#about) · [Get in touch](mailto:jeongc@usc.edu)

</div>

---

## About

Hi, I’m Christine—a senior at the University of Southern California studying **Computer Science & Business Administration**, with a minor in **Web Development**.

I work at the intersection of software engineering and user-centered design. This portfolio brings together the systems I build, the interfaces I design, and the thinking that connects them.

## Selected work

| Project | Focus | Explore |
| --- | --- | --- |
| **A.X K1 Agent Demo** | A map-based AI agent built during my Rebellions internship, combining model-driven tool calling, live TMAP data, and NPU serving. | [Case study & final demo](https://christinejeong.github.io/Portfolio/k1_demo.html) |
| **Sori.ai** | A sound-recognition experience designed during my Cochl internship, bringing contextual audio insights into a calm, personalized interface. | [Design case study](https://christinejeong.github.io/Portfolio/sori.html) |
| **Trojan Trade** | A USC marketplace concept for buying, selling, and renting preloved essentials, with interactive search, saved items, and demo listings. | [Try the demo](https://christinejeong.github.io/Portfolio/trojan-trade.html) · [Source repository](https://github.com/christinejeong/trojan-trade) |
| **Subly** | A student subleasing concept shaped by user research, personas, and the challenges of finding a temporary home. | [Design case study](https://christinejeong.github.io/Portfolio/subly.html) |

## The website

The site pairs a warm paper palette with blue ink, expressive typography, and small interactive details:

- **An interactive home page** with animated lettering and a canvas visitors can draw on.
- **Smooth project entrances** with staggered cards and reduced-motion support.
- **Responsive navigation** with a consistent SVG identity on desktop and mobile.
- **Individual project pages** for context, process, diagrams, and final outcomes.
- **Working demos** that let visitors explore the interactions themselves.

### Built with

**HTML · CSS · Vanilla JavaScript · SVG · Canvas**

The portfolio is a static website hosted on **GitHub Pages**. There is no framework build step or package installation required to preview it. Technologies used within individual projects are described on their respective pages.

## Run locally

Clone the repository:

```sh
git clone https://github.com/christinejeong/Portfolio.git
cd Portfolio
```

Start a local server with Python 3:

```sh
python3 -m http.server 8765
```

Open **http://localhost:8765/portfolio.html**.

> The main entry point is `portfolio.html`, rather than `index.html`.

## Repository guide

```text
Portfolio/
├── portfolio.html          # Main home, about, and projects experience
├── portfolio-nav.css       # Shared logo and responsive navigation styles
├── k1_demo.html             # Rebellions internship case study and final video
├── sori.html               # Sori.ai / Cochl internship case study
├── subly.html               # Subly case study
├── trojan-trade.html        # Trojan Trade marketplace demo
├── trojan-trade/            # Marketplace behavior, styling, and assets
├── img/                    # Project covers and portfolio imagery
└── fonts/                  # Local font assets
```

Additional pages and project asset folders are retained alongside these entry points.

## Updating the portfolio

1. Edit the relevant HTML, CSS, JavaScript, or assets.
2. Preview locally and check the affected page at desktop and phone widths.
3. Commit and push the changes to the branch used by GitHub Pages.

Keep relative asset paths intact so pages work beneath the `/Portfolio/` URL. When adding a project cover or shared stylesheet, include the new file in the same commit as the page that references it.

### A note on the demos

Trojan Trade uses illustrative listings and browser-local storage. Messages are previews; there is no connected marketplace backend, student verification, or payment flow. Its standalone repository contains the same redesigned experience, with its own deployment setup.

## Let’s connect

Interested in software, AI, or thoughtful product experiences?

[**Email me**](mailto:jeongc@usc.edu) · [**GitHub**](https://github.com/christinejeong) · [**Visit the portfolio**](https://christinejeong.github.io/Portfolio/portfolio.html)
