# LCARS Theme

An LCARS theme for Quarto HTML formats.

## Installing

To install the format with a `template.qmd` file that you can use as a starting place use:

```bash
quarto use template mccarthy-m-g/quarto-lcars-theme
```

To install the format without the template into an existing project or directory use:

```bash
quarto add template mccarthy-m-g/quarto-lcars-theme
```

## Using 

To use the format, you can use the format name `lcars-html`. For example:

```bash
quarto render template.qmd --to lcars-html
```

or in your document yaml:

```yaml
format:
  lcars-html: default
```
