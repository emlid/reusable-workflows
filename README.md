# reusable-workflows

This repo contains [reusable workflows](https://docs.github.com/en/actions/using-workflows/reusing-workflows) for github actions.

## Workflows
This repo contains the following workflows:

- `trivy` - install [trivy](https://github.com/aquasecurity/trivy) and check vulnerabilities in docker images
- `pythonlint` - install [tox](https://tox.wiki/en/latest/) and run python linter
- `gitlint` - run gitlinter to check the commits in the pull request
- `dockerlint` - run [hadolint](https://github.com/hadolint/hadolint) over the project's dockerfiles
- `docker-build-push` - build docker images and push them to DO docker registry
- `docker-add-version-and-latest-tags` - add `latest` and `github.event.release.tag_name` tags to docker images
