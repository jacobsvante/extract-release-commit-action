<!-- action-docs-description -->

## Description

Used to extract the release version from a release-please formatted commit.

<!-- action-docs-description -->

Example of a [release-please](https://github.com/googleapis/release-please) release commit message: `chore(main): release 0.7.12`

<!-- action-docs-inputs -->

## Inputs

| parameter      | description                                                                                                        | required | default |
| -------------- | ------------------------------------------------------------------------------------------------------------------ | -------- | ------- |
| commit-message | Used to manually provide a comnmit message, in case `github.event.head_commit.message` is not what should be read. | `false`  |         |

<!-- action-docs-inputs -->

<!-- action-docs-outputs -->

## Outputs

| parameter | description                                                                                           |
| --------- | ----------------------------------------------------------------------------------------------------- |
| version   | The extracted version. An empty string `""` if it could not be extracted (i.e. not a release commit.) |

<!-- action-docs-outputs -->

<!-- action-docs-runs -->

## Runs

This action is a `composite` action.

<!-- action-docs-runs -->
