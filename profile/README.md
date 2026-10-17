<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/capro-uio/.github/main/profile/assets/capro-logo-dark.png">
    <img alt="CAPRO — UiO: Life science" src="https://raw.githubusercontent.com/capro-uio/.github/main/profile/assets/capro-logo-light.png" width="420">
  </picture>
</p>

<p align="center">
  <strong>Capture and Processing of Lifescience data for Social Sciences and Humanities</strong><br>
  Data capture and processing support at the University of Oslo
</p>

<p align="center">
  <a href="https://www.capro.dev/">Website</a> &nbsp;·&nbsp;
  <a href="https://www.capro.dev/#services">Services</a> &nbsp;·&nbsp;
  <a href="https://www.capro.dev/#team">Team</a> &nbsp;·&nbsp;
  <a href="https://capro-uio.r-universe.dev/">R-universe</a> &nbsp;·&nbsp;
  <a href="https://app.reclaim.ai/m/capro/initiating-talks">Book a consultation</a>
</p>

---

Capturing and processing large data sets is increasingly central to the social
sciences and humanities, but the technical work rarely fits neatly into a
research project's plan. We build and maintain the tooling that makes that work
tractable — from data capture and secure storage, through reproducible
processing on HPC, to the software your team actually runs day to day.

Everything in this organisation is open source, and most of it started as
something a researcher at UiO needed and could not find elsewhere.

## What we work on

| | |
|---|---|
| **Data capture** | Getting data out of surveys, registries and instruments in a form you can work with. |
| **Data engineering** | Cleaning, lineage, and secure management of project data on UiO infrastructure — Nettskjema, TSD, Educloud, NREC. |
| **High performance computing** | Setting up and running parallel analyses of large, complex datasets. |
| **Applications & databases** | Custom web tools for tracking data, processing status and project state. |
| **Reproducibility** | Containerised workflows, pinned environments, and analysis that still runs next year. |
| **Training** | Hands-on workshops in R, project management and modern scientific workflows. |

## Tools we maintain

**R packages** — install from our [R-universe](https://capro-uio.r-universe.dev/):

```r
install.packages(
  c("nettskjemar", "tsdrtools", "uiothemes", "neuromat"),
  repos = c("https://capro-uio.r-universe.dev", "https://cloud.r-project.org")
)
```

| Package | What it does |
|---|---|
| [**nettskjemar**](https://github.com/capro-uio/nettskjemar) | Work with the University of Oslo's Nettskjema survey API from R. |
| [**tsdrtools**](https://github.com/capro-uio/tsdrtools) | Install R packages inside TSD, UiO's closed secure server. |
| [**uiothemes**](https://github.com/capro-uio/uiothemes) | UiO branding for plots, documents and reports. |
| [**neuromat**](https://github.com/capro-uio/neuromat) | Build model matrices for neuroimaging analyses. |
| [**nva**](https://github.com/capro-uio/nva) | Interface to the Nasjonalt Vitenarkiv (NVA) API. |
| [**ebrains.kg**](https://github.com/capro-uio/ebrains.kg) | Interface to the EBRAINS Knowledge Graph API. |

**Other projects:**

| Project | What it does |
|---|---|
| [**jspsych-studio**](https://github.com/capro-uio/jspsych-studio) | No-code builder for jsPsych experiments — author in the browser, export readable jsPsych you can host anywhere. |
| [**capro.pkgdown**](https://github.com/capro-uio/capro.pkgdown) | pkgdown template giving our R packages a consistent look. |
| [**js_datainspector**](https://github.com/capro-uio/js_datainspector) | Small web app for correcting incoming Nettskjema data without touching the originals. |

## Working with us

We take on projects with research groups at UiO and beyond. If you are planning
a study and the data side feels like it might become a problem later, that is
exactly the point at which it is cheapest to talk to us.

[Book a consultation](https://app.reclaim.ai/m/capro/initiating-talks) or read
more about [what we offer](https://www.capro.dev/#services).

## Contributing

Issues and pull requests are welcome on any of our repositories. Our
[code of conduct](https://github.com/capro-uio/.github/blob/main/CODE_OF_CONDUCT.md)
and [contributing guide](https://github.com/capro-uio/.github/blob/main/CONTRIBUTING.md)
apply across the organisation.

<p align="center">
  <sub>Harald Schjelderups hus, Forskningsveien 3A, 0373 Oslo, Norway</sub>
</p>
