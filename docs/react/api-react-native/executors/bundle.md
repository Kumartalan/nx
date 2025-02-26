# @nrwl/react-native:bundle

Builds the JS bundle.

Options can be configured in `workspace.json` when defining the executor, or when invoking it.
Read more about how to use executors and the CLI here: https://nx.dev/getting-started/nx-cli#common-commands.

## Options

### bundleOutput (_**required**_)

Type: `string`

The output path of the generated files.

### entryFile (_**required**_)

Type: `string`

The entry file relative to project root.

### platform (_**required**_)

Type: `string`

Platform to build for (ios, android).

### dev

Default: `true`

Type: `boolean`

Generate a development build.

### maxWorkers

Type: `number`

The number of workers we should parallelize the transformer on.

### sourceMap

Type: `boolean`

Whether source maps should be generated or not.
