![on-push](../../actions/workflows/on-push.yaml/badge.svg)
![on-pull-request](../../actions/workflows/on-pull-request.yaml/badge.svg)
![on-schedule](../../actions/workflows/on-schedule.yaml/badge.svg)

# Bioinformatics & Computational Genomics Lab website

Visit **[www.southerngenomics.org](https://www.southerngenomics.org)** 🚀

Website of the Yao-Cheng Lin lab, Academia Sinica.

## Editing

This site is maintained by Yao-Cheng Lin, the only person with write access.
Lab members: please email changes (text, photos, ORCID iD) to Yao-Cheng, or open an issue.

| To change | Edit |
|---|---|
| Home page | `index.md` |
| Research themes | `research/index.md` |
| Publications page | Automatic from the PI's ORCID in `_data/orcid.yaml` + `_data/sources.yaml` (don't edit `_data/citations.yaml`) |
| A member's own paper list | `<member-file>: true` on their entry in `_data/orcid.yaml` |
| News | add `_posts/YYYY-MM-DD-short-title.md` |
| Team | `_members/<name>.md`, photo in `images/team/` |
| Tools, data, platforms | `_data/projects.yaml`, pages in `resources/` |
| Lab only links | `resources/lab-only.md` |
| Contact | `contact/index.md` |
| Site title, links, header image | `_config.yaml` |

Commit to `main` to publish (about 3 minutes), or use a branch + pull request to get a preview link first.

## Acknowledgements

_Built with [Lab Website Template](https://greene-lab.gitbook.io/lab-website-template-docs)_ by the [Greene Lab](https://github.com/greenelab/lab-website-template) (BSD-3-Clause, see `LICENSE.md`),
with design inspiration from the [Ecological Complexity Lab website](https://github.com/Ecological-Complexity-Lab/lab_website) and [blotter](https://github.com/blab/blotter) by the [Bedford Lab](https://bedford.io).
