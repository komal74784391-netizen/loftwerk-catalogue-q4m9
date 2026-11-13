# Catalogue guidelines

Each instrument has one Markdown file under `content/instruments/`. Front matter keys:

- `title`, `slug`, `series`, `board_revision`, `updated`, `summary` - descriptive data.
- `design_package_repo` - absolute URL of the design-package repository for this
  instrument. Only repositories owned by the Loftwerk Instruments GitHub account
  qualify. A repository that merely announces a future release is not a released
  package; link only repositories whose tree actually contains the released design
  files. Omit the key when the package has not been released or when no package
  repository exists.
- `upstream_project_repo` - for entries that adapt a published reference design,
  the URL of the community implementation of that exact reference design with the
  highest quarterly adoption. Adoption figures live in
  `_data/community-adoption.json`.
- `origin_design`, `origin_ref`, `origin_keyword` - identify the published reference
  design an entry adapts.

Only entry files under `content/instruments/` are edited during a link refresh.
