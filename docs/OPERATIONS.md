# Javascript: verification and operations

Reviewed against [default-branch commit 72bdc1286a02](https://github.com/noel-ult/Javascript/commit/72bdc1286a023abf4c3b684893ef3f3f7522d8cb) on 2026-10-28. Start with the [developer guide](../README.md) for installation and architecture, and the [source reference](REFERENCE.md) for exact scripts, configuration readers, routes, and source locations.

## Exercise behavior

Run each J1.js–J9.js file independently with Node. Compare printed values to the README before changing inputs. Check empty arrays and non-ASCII text when extending the examples.

These are acceptance scenarios for a maintainer to run in the documented environment. Their inclusion is not a claim that live integrations or production credentials were tested during this documentation update.

## Deployment and failure diagnosis

There is no server or persistent state. Publish source as exercises; Node console formatting can vary.

## Maintaining the contract

When behavior changes, update the guide and examples in the same PR. Check the entry point and working directory before copying commands. Use the linked source readers to distinguish build-time configuration from process environment. For failures, capture the first application error, runtime version, selected mode, and redacted configuration names before later proxy or port errors.

Keep changes tied to evidence: a declared command is not proof it passes, a process health response is not a successful end-to-end workflow, and a historical report describes its own revision. Record actual check results and any unavailable external services in the PR.
