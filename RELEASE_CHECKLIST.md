# Grid release checklist

## Grid-ui
- [ ] Merge `dev` into `master`

## Grid
- [ ] Bump version on `grid/package.json`
- [ ] Push to `master` branch
- Check codesign certificates for apps:
  - [ ] mac
  - [ ] win

## Release pipeline
- [ ] Check if the correct artifacts were uploaded to a github release draft
- [ ] Double-check artifacts version against latest grid app
- [ ] Smoke test on three architectures (can use amazon workspaces for that)
- [ ] Write release notes when relevant
- [ ] Publish release
- [ ] Rebuild github pages to display the latest release (`git commit -m "docs: pages rebuild" --allow-empty && git push origin master`)


# TODO
- [ ] Publish to yum registry
- [ ] Publish to APT
- [ ] 

