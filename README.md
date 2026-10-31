# DoofPlus Landing Page

Landing Page of **DoofPlus**, the quality management and batch traceability platform for pharmaceutical laboratories, built by IngesCompany. It presents the value proposition to QA/QC specialists and production supervisors and ends with a call to action for each segment, which opens the corresponding view of the DoofPlus Web Application.

- Published site: https://ingescompany-7742.github.io/IngesCompany-LandingPage/
- Web Application: https://doofplus-webapp.web.app

## Technologies

HTML5, CSS3 and JavaScript (ES modules), with no framework. Texts in English (default) and Latin American Spanish.

## Run locally

```bash
npm install
npm start
```

The site opens at `http://localhost:8080` with the browser cache disabled. On `localhost`, the sign-in and call to action buttons open the Web Application running locally at `http://localhost:4200` (`ng serve`); on any other host they open the published Web Application.

## Structure

```text
index.html              Landing Page
terms.html, privacy.html  Legal pages linked from the footer
404.html                Page shown by GitHub Pages for unknown paths
public/assets/
  i18n/                 English and Spanish texts (en.json, es.json)
  images/               Logo and pictures
  scripts/              Entry point (main.js), settings (config.js), i18n and one module per component
  styles/               Variables, reset, layout, grid, components, sections and responsive rules
docs/                   User stories of the Landing Page
```

## Contributing

The repository follows GitFlow (`main`, `develop`, `feature/*`, `release/*`, `hotfix/*`), Conventional Commits and Semantic Versioning.

## License

MIT, see [LICENSE.txt](LICENSE.txt).
