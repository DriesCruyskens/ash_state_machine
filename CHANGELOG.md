# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](Https://conventionalcommits.org) for commit guidelines.

<!-- changelog -->

## [v0.1.0](https://github.com/ash-project/ash_state_machine/compare/v0.1.0...v0.1.0) (2023-04-23)




### Features:

* add mix task `ash_state_machine.generate_flow_charts` (#1)

### Bug Fixes:

* action does not uniquely identify a transition

* require `allow_nil? false` on state attribute

### Improvements:

* require `initial_states`

* fix lint/credo, handle all changeset types

* require from/to

* flow chart generation

* support `:*` as a transition action name to match all