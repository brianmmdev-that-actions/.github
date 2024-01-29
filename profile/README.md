# Actions for THAT

Hey! I'm Brian Morrison II, and I created this organization to be the home for my demos and samples given at THAT Conference in 2024 at the Kalahari Resort in Austin, TX.

Feel free to contact me on Twitter [@brianmmdev](https://twitter.com/brianmmdev) if you have any questions, or email me at brian@brianmorrison.me.

## Slides

For access to the slides, check the `slides` folder at root of this repository. It contains screenshots of all slides. 

Any sample videos presented during the talk are nested in the `videos` folder.

## Directory

Here is a list of the repositories in this organization:

- [brianmmdev-that-actions/public-action](https://github.com/brianmmdev-that-actions/public-action) contains a very simple hello world Action.
- [brianmmdev-that-actions/public-workflow](https://github.com/brianmmdev-that-actions/public-workflow) contains a workflow that utilizes public-action.
- [brianmmdev-that-actions/ghcr-base-image-with-dep](https://github.com/brianmmdev-that-actions/ghcr-base-image-with-dep) is the source code for a docker image that runs a Go action, but also imports a private go package.
- [brianmmdev-that-actions/docker-sh-action](https://github.com/brianmmdev-that-actions/docker-sh-action) has a sample Action that is built using bash.
- [brianmmdev-that-actions/private-workflow](https://github.com/brianmmdev-that-actions/private-workflow) is where nearly all of the use cases shown during the talk were executed.
- [brianmmdev-that-actions/docker-js-action](https://github.com/brianmmdev-that-actions/docker-js-action) shows an Action built with Docker that utilizes NPM,
- [brianmmdev-that-actions/private-go-package](https://github.com/brianmmdev-that-actions/private-go-package) is a simple Go package that is simply in a private repository, used as part of one of the demos.
- [brianmmdev-that-actions/private-action](https://github.com/brianmmdev-that-actions/private-action) contains a simple hello world Action, but is in a private repository.
- [brianmmdev-that-actions/ghcr-base-image](https://github.com/brianmmdev-that-actions/ghcr-base-action) is the source for the base image used in the security and access part of the demos.
- [brianmmdev-that-actions/ghcr-base-action](https://github.com/brianmmdev-that-actions/ghcr-base-image) is the Action that calls `ghcr-base-action`.

## External resources

These are helpful resources that are not in the organization and may have not been directly part of the demo, but I felt they were worth including to add value:

- [planetscale/create-branch-action](https://github.com/planetscale/create-branch-action) is the source for the PlanetScale Action referenced most during the talk.
- [planetscale/create-branch-password-action](https://github.com/planetscale/create-password-branch-action) is the source for the Action that creates a password for a branch, used during the Outputs section of the talk.
- [https://docs.github.com/en/actions/using-workflows/workflow-syntax-for-github-actions] is the docs page describing the syntax for the workflow yaml and all possible options and values.
- [https://docs.github.com/en/actions/creating-actions/metadata-syntax-for-github-actions](https://docs.github.com/en/actions/creating-actions/metadata-syntax-for-github-actions) is the docs page describing the syntax for the action yaml file.
- [sdras/awesome-actions](https://github.com/sdras/awesome-actions) is a fantastic repository containing many different use cases and samples for Actions.
