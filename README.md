# GenGen Content

Official themes and templates for [GenGen](https://github.com/kingwill101/gengen) static site generator.

## Usage

Add to your `config.yaml`:

```yaml
module:
  imports:
    - path: github.com/kingwill101/gengen_content
      version: ^1.0.0

theme: minimal  # or: starter, default, aurora
```

Then run:

```bash
gengen mod get
gengen build
```

## Themes

| Theme | Description |
|-------|-------------|
| `themes/minimal` | Clean, minimal blog theme |
| `themes/starter` | Full-featured starter theme |
| `themes/default` | Simple default theme |
| `themes/aurora` | Modern theme with hero sections |

## Templates

| Template | Description |
|----------|-------------|
| `templates/blog` | Blog site with posts |
| `templates/docs` | Documentation site with sidebar |

## Structure

```
gengen_content/
├── themes/
│   ├── minimal/      # Minimal blog theme
│   ├── starter/      # Feature-rich starter
│   ├── default/      # Simple default
│   └── aurora/       # Modern with hero
└── templates/
    ├── blog/         # Blog site template
    └── docs/         # Documentation template
```

## License

MIT
