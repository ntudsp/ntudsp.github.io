# NTU DSP Lab GitHub Pages Website

This repository hosts the public GitHub Pages website for the NTU Digital Signal Processing Laboratory.

## Website purpose

The site acts as a professional landing page for:

- group publications
- datasets and benchmark resources
- source code repositories
- software tools and demonstrations
- reproducible research outputs

## Publication updates

Publication entries are loaded dynamically from:

```text
https://github.com/ntudsp/citation-list-dsplab
```

To update publications, edit `publication_list.csv` in `ntudsp/citation-list-dsplab`. The website fetches that CSV directly from GitHub and renders visible entries.

## Repository/resource updates

Featured datasets and software links are currently configured in `index.html` under the `curatedResources` and `preferredRepos` JavaScript constants.

Recommended update workflow:

1. Add or update the relevant public repository in the `ntudsp` GitHub organization.
2. Add the repository name to `preferredRepos` if it should appear in the source-code section.
3. Add a curated entry to `curatedResources.datasets` or `curatedResources.software` if it should appear in the featured resource section.

## Deployment

This is an organization GitHub Pages repository. The website is served from the `main` branch at:

```text
https://ntudsp.github.io
```

No build system is required. The site is a self-contained static `index.html` file.
