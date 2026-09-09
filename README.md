# Culture & Practices

A single-page Hugo site publishing how our team works. It is deployed to GitLab
Pages by `.gitlab-ci.yml` on every push to `main`.

The page itself lives in `content/_index.md`. The theme is
[PaperMod](https://github.com/adityatelange/hugo-PaperMod), pulled in as a git
submodule under `themes/PaperMod`; put overrides in `layouts/` rather than
editing the theme.

## Local preview

```
git submodule update --init
hugo server
```
