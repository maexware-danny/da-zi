# About Me Docusaurus

Personal about-me site built with Docusaurus.

## Local DDEV deployment

```bash
ddev start
ddev npm install
ddev npm run build
ddev launch
```

DDEV serves the static output from `build/`. After edits, run:

```bash
ddev npm run build
ddev launch
```

For Docusaurus' live development server:

```bash
ddev npm run start
```

Then open the forwarded DDEV URL for port `3000`, or run the same command outside DDEV and open `http://localhost:3000`.

## Webserver deployment

Build the site and copy the generated `build/` directory to your webserver document root.
