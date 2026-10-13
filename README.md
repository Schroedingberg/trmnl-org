# GTD Next Actions - From Org

A [TRMNL](https://trmnl.com) plugin for ePaper displays, connected by
[GitHub Sync](https://help.trmnl.com/en/articles/15977899-github-sync): every save in TRMNL lands here as a commit. (While that is true, manual commits also land here. I just accepted the sync to make the linter happy.)

<img width="150" alt="image" src="https://trmnl.com/images/brand/badges/light/works-with-trmnl/trmnl-badge-works-with-light.svg" />



I wanted to render my org agenda on the trmnl, so I built this.
It is currently in early alpha mode.
I wanted a solution that works for me - I might never take the time to polish this.

### Develop locally

Templates and settings live in [`src/`](src/), ready for [trmnlp](https://github.com/usetrmnl/trmnlp):

```sh
gem install trmnl_preview
trmnlp serve
```

Find example data in `.trmnlp.yml` - these should help you get started if you want to work on the templates.

I feed data to this with a tool that currently runs on my machine and is not yet published.

### Tests
Tests will be available as soon as the webhook service is published.


