Andover Town Charter — Plain-Language Guides
============================================

Plain-language guides to Andover, CT's town charter and governance, converted
from Markdown sources to a static HTML site.


Quick start
-----------

```bash
npm install
npm run convert
```

This reads the Markdown sources from `sources/` and generates HTML into the
project root.


Sources
-------

The Markdown files in `sources/` were written by consulting:

- A local copy of the 2024 charter (in TiddlyWiki format)
- Connecticut General Statutes at https://www.cga.ct.gov/current/pub/titles.htm

The `pages.json` file maps each source document to its output path and title.


Output structure
----------------

| Path                    | Document                                      |
| ----------------------- | --------------------------------------------- |
| `index.html`            | Index / landing page                          |
| `budget/`               | The Annual Budget Process                     |
| `town-meetings/`        | Town Meetings                                 |
| `governance/`           | Governance Structure                          |
| `spending/`             | Spending Beyond the Annual Budget             |
| `appointments/`         | Appointments, Vacancies, and Removals         |
| `elections/`            | Elections                                     |


Deployment
----------

This information is deployed to http://charter.andoverct.info.