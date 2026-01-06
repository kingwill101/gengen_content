# GenGen Content

A collection of themes and plugins for [GenGen](https://github.com/kingwill101/gengen) static site generator.

## Themes

### gengen-theme-minimal

A lightweight minimal theme for new GenGen sites.

```yaml
module:
  imports:
    - path: github.com/kingwill101/gengen_content
      version: ^1.0.0

theme: gengen-theme-minimal
```

### gengen-theme-starter

A full-featured starter theme with aurora styling.

```yaml
module:
  imports:
    - path: github.com/kingwill101/gengen_content
      version: ^1.0.0

theme: gengen-theme-starter
```

## Installation

Add the module to your GenGen site's config:

```yaml
module:
  imports:
    - path: github.com/kingwill101/gengen_content
      version: ^1.0.0
```

Then run:

```bash
gengen mod get
```

## License

MIT
