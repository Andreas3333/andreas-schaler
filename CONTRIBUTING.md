# Contributing

## Publishing new versions

The procedure for pushing new versions of aboutme is -

- Push changes to branch `feature-foo`
- Make up a PR for the changes
- Merge PR into main (using a squash and merge PR).
- GH Action Job runs the `mkdocs gh-deploy` cmd which pushes the built documentation content to the `gh-pages` repo 
  branch.
- GH Pages serves the content located in `root/` of the `gh-pages` branch.
