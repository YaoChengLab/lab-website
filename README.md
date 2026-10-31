![on-push](../../actions/workflows/on-push.yaml/badge.svg)
![on-pull-request](../../actions/workflows/on-pull-request.yaml/badge.svg)
![on-schedule](../../actions/workflows/on-schedule.yaml/badge.svg)

# Bioinformatics & Computational Genomics Lab website

Visit **[www.southerngenomics.org](https://www.southerngenomics.org)** 🚀

Website of the Yao-Cheng Lin lab, Academia Sinica.

## Editing

| To change | Edit |
|---|---|
| Home page | `index.md` |
| Research themes | `research/index.md` |
| Publications | Automatic from `_data/orcid.yaml` + `_data/sources.yaml` (don't edit `_data/citations.yaml`) |
| News | add `_posts/YYYY-MM-DD-short-title.md` |
| Team | `_members/<name>.md`, photo in `images/team/` |
| Tools, data, platforms | `_data/projects.yaml`, pages in `resources/` |
| Contact | `contact/index.md` |
| Site title, links | `_config.yaml` |

Make changes on a branch and open a pull request: a bot comments with a preview link.
Merging to `main` publishes the site in a few minutes.

## Acknowledgements

_Built with [Lab Website Template](https://greene-lab.gitbook.io/lab-website-template-docs)_ by the [Greene Lab](https://github.com/greenelab/lab-website-template) (BSD-3-Clause, see `LICENSE.md`),
with design inspiration from the [Ecological Complexity Lab website](https://github.com/Ecological-Complexity-Lab/lab_website) and [blotter](https://github.com/blab/blotter) by the [Bedford Lab](https://bedford.io).
