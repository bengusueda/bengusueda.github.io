# Bengü Süeda Şengül’s academic website

A GitHub Pages / Jekyll website based on the academic homepage template in `../alibrahimzada.github.io`. Content is transcribed from `CV_2026.pdf`.

## Editing

- `_data/profile.json`: identity, contact details, and education.
- `_data/experience.json`: research and professional experience.
- `_data/publications.json`: citations and DOI links.
- `_data/teaching.json`, `_data/service.json`, `_data/awards.json`, `_data/talks.json`, `_data/workshops.json`: CV sections.
- `_pages/`: homepage and section pages.
- `assets/css/global.css` and `assets/css/site.css`: retained template styling and adaptations.
- `CV_2026.pdf`: downloadable source CV.

The profile uses initials until a portrait is supplied. To add a portrait, replace the monogram in `_includes/widgets/profile_card_mini.html` with an image from `assets/img/`.

## Local preview

Run:

```sh
./run.sh
```

The script finds Ruby 3 or newer, installs missing dependencies into `vendor/bundle`, and starts Jekyll. The first run needs an internet connection to download dependencies. If Ruby is unavailable, install it with `brew install ruby`.

Open `http://localhost:4000`. Stop the server with Ctrl+C. Extra Jekyll options are forwarded, for example `./run.sh --port 4001`.

## GitHub Pages

This site uses plugins supported by GitHub Pages and does not need the template’s custom Scholar plugins. In the repository’s **Settings → Pages**, choose **Deploy from a branch**, select the source branch and `/ (root)`. GitHub Pages builds the site after changes are pushed. The configured URL is `https://bengusueda.github.io`.

Publication statuses are preserved from the CV, including the ACS Nano entry’s “accepted, in revision” wording and the bioRxiv preprint designation.
