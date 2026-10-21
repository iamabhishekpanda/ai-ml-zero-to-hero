# Technology Guides

By Abhishek Panda — Enterprise AI Solution Architect.

## Read

- `index.html`: technology-guides home page and default static-site entry point.
- `ai-solution-architect-curriculum.html`: AI / ML curriculum and deep-learning learning path.
- `azure-services.html` and `aws-services.html`: modular cloud-service learning guides.
- `abhishek-panda.jpg`: author portrait and favicon.
- `assets/AbhishekPanda_CV.pdf`: downloadable CV linked from the header.
- `assets/company-logos/`: local logo assets from Abhishek Panda’s portfolio; source links are recorded in `assets/company-logos/SOURCES.md`.
- `handbook.html`: companion handbook with three existing chapter pages.
- `CURRICULUM-PUBLISHING.md`: verification notes and publication limitations.

## Preview and publish

Open `index.html` in a browser, or run `python3 -m http.server 8000` and visit `http://localhost:8000`.

Live site: https://iamabhishekpanda.github.io/ai-ml-zero-to-hero/

GitHub Pages publishes the `main` branch root and serves its `index.html` as the site homepage. Push changes to `main` to update the site. Keep the HTML pages, portrait, and `assets/` directory together. No build step is needed. Learning progress is stored in the reader’s browser; use the curriculum’s export/import controls to transfer it. Progress from local files does not automatically transfer to the hosted origin.

The homepage is a standalone guide directory; its AI / ML card opens the curriculum. Edit each guide page directly.
