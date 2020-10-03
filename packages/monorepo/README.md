# @loopback/monorepo

This module contains a set of common scripts to maintain lerna managed monorepo.

- check-package-locks: check if `package-lock.json` files has local packages.
- rebuild-package-locks: rebuild `package-lock.json` files for all packages or
  packages matching given scopes.
- run-lerna: run `lerna` command with `LERNA_ROOT_PATH` environment variable set
  to the root path of the monorepo
- config-lerna-scopes: return a list of scope names for conventional commits.
- update-package-deps: update package dependencies to match versions of local
  packages.
- update-package-json: update `package.json` files for all packages based on
  metadata from the root `package.json` for the monorepo
- update-ts-project-refs: update `tsconfig.json` with TypeScript project
  references based on the dependency graph.

## Basic use

To use `@loopback/monorepo` for your package:

1.  Run the following command to add `@loopback/monorepo` as a dev dependency.

`npm i @loopback/monorepo --save-dev`

## Contributions

- [Guidelines](https://github.com/strongloop/loopback-next/blob/master/docs/CONTRIBUTING.md)
- [Join the team](https://github.com/strongloop/loopback-next/issues/110)

## Tests

run `npm test` from the root folder.

## Contributors

See
[all contributors](https://github.com/strongloop/loopback-next/graphs/contributors).

## License

MIT
