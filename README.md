# README

To trigger a Github action workflow with a workflow,
you need to setup both source repo and target repo.

Take a look on workflow files for details.

- [Source workflow file](https://github.com/lightyears1998/test-github-actions-event-source/blob/master/.github/workflows/main-action.yml) (The workflow which triggers the other one.)
- [Target workflow file](https://github.com/lightyears1998/test-github-actions-event-target/blob/master/.github/workflows/main-action.yml) (The workflow which is triggered.)

You may also be interested in [`repository_dispatch` event](https://help.github.com/en/actions/reference/events-that-trigger-workflows#external-events-repository_dispatch).
