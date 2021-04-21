# Alchemist Shared Components

Shared react components across Alchemist.

## Usage

### `npm run build`

Concurrently builds all packages.

### `npm run start`

Installs dependencies across all packages and conccurently starts server.

### `npm run lint`

Concurrently ints all packages.

### `npm run lint:fix`

Concurrently lint fixes all packages.

### `npm run clean`

Removes `node_modules` in root and across all packages.

### `npm version:packages`

Uses changeset to bump package versions using conventional commits.
This is normally executed by our Github Action.

#### See More

Changesets: [https://github.com/atlassian/changesets](https://github.com/atlassian/changesets)
Changesets Action: [https://github.com/changesets/action](https://github.com/changesets/action)
Example output: [https://github.com/chakra-ui/chakra-ui/pull/3813](https://github.com/chakra-ui/chakra-ui/pull/3813)
