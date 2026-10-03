# Contributing

Thanks for helping grow this curated list of use cases attributed to Claude Fable 5.5.

## What belongs here

Use cases — playable games, interactive 3D, films, agent or engineering showcases, and related collections — whose public source says they were built with or prominently feature **Claude Fable 5.5**.

Do not add official-sounding specs, prices, or benchmarks unless they come from an Anthropic page. As of 2026-10-03 the public catalog still lists Fable 5.1. Pure prompt dumps do not belong in the main sections.

## How to add an entry

Update both:

1. `README.md`
2. `data/usecases.json`

Required fields: `title`, `url`, `description`, `source` (`github`, `x`, `hn`, `web`, or `official`).

Optional: `demo_url`, `stars`, `notes`, `category` (`games-3d`, `creative`, `agent`, `collections`, `benchmarks`, `showcase`, `videos`), `author` (required for X videos), `video_type`.

```json
{
  "id": "kebab-case-slug",
  "title": "Demo Title",
  "url": "https://github.com/org/repo",
  "demo_url": null,
  "source": "github",
  "category": "games-3d",
  "stars": null,
  "notes": "The source says Fable 5.5 was used",
  "added": "2026-10-03"
}
```

X videos must link `https://x.com/<handle>/status/<id>`, credit `@handle`, and be listed once.

## Checklist

- [ ] The link resolves and the source itself says Fable 5.5
- [ ] Not a duplicate
- [ ] README and `data/usecases.json` match

## License

Additions are released under [CC0 1.0](LICENSE).
