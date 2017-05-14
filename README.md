# bitrise-plugin-step

Bitrise Plugin to interact with steps, list them, retrieve information, or create your own!

## WIP

- prepare everything for "share"
- update the generated README template, to use the step create plugin instead of the previous, manual step template copying

## How to release this plugin

- `git checkout master`
- bump `RELEASE_VERSION` in `bitrise.yml`
- commit the change(s)
- call `bitrise run create-release`
- check and update the generated `CHANGELOG.md`
- test the generated binaries in `_bin/` directory
- push these changes to the `master` branch
- once `deploy` workflow finishes on bitrise.io create a github release with the generated binaries


