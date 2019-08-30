# Circle CI Node and AWS CLI

Each push will result in an image being tagged with `latest`. If a release needs to be done, then git tag must be created:
- `git tag -a <major>.<minor> -m "relase"` (e.g. `git tag -a 10.13 -m "relase"`)
- `git push --tags`
