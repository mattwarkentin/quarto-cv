# Quarto Curriculum Vitate Extension

This repository contains a simple curriculum vitae (CV) format for the Quarto technical publishing system.

# Usage

## Creating a new CV

```sh
quarto use template mattwarkentin/quarto-cv
```

## Installing extension for existing Quarto document

```sh
quarto install extension mattwarkentin/quarto-cv
```

## Format Options

There are several options available for this format, to use these options, include them in your YAML frontmatter as follows:

```yaml
format:
  cv-pdf:
    option: value
```

- `email` - Email address

- `phone` - Phone number

- `github` - GitHub user name

- `twitter` - Twitter handle

- `web` - Personal website URL

- `orcid` - ORCID identifier

- `scholar` - Google Scholar identifier

- `logo` - Relative path to a logo that should be included in the top right corner of the first page?

- `section-rules` - Should section rules (i.e., lines) be included after top-level headers? `true` or `false` (default is `false`)

- `updated` - Should the title block include text about the date the CV was last updated? `true` or `false` (default is `true`)
