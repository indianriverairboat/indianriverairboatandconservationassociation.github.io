# indianriverairboatandconservationassociation.github.io

Website for the Indian River Airboat and Conservation Association, built with Jekyll on GitHub Pages.

## Where the content lives

| What | Where | Edited in Pages CMS as |
| --- | --- | --- |
| Dated events | `_events/*.md` | Events |
| News posts | `_news/*.md` | News |
| Page text (headline, About, cards, contact info, banner) | `_data/site.yml` | Site text |
| Uploaded flyers and photos | `images/uploads/` | Media |

The layout and styles are in `index.html`. The editor forms are defined in `.pages.yml`.

Events whose date has passed are hidden automatically: the page script hides them in the browser, and `.github/workflows/nightly-rebuild.yml` rebuilds the site every night.
