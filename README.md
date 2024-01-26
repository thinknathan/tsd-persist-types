<img src="_docs/tsd-persist-types.png" alt="Persist Types">

# @types/tsd-persist-types

<a href="https://discord.gg/eukcq5m"><img alt="Chat with us!" src="https://img.shields.io/discord/766898804896038942.svg?colorB=7581dc&logo=discord&logoColor=white"></a>

TypeScript types for Klayton Kowalski's [Persist](https://github.com/klaytonkowalski/library-defold-persist), a simple interface for saving and loading data in a Defold game engine project.

For use with [TS-Defold](https://github.com/ts-defold) and [TypeScriptToLua](https://github.com/TypeScriptToLua).

## Installation

```bash
yarn add git+https://git@github.com/thinknathan/tsd-persist-types.git#^0.0.1 -D
# or
npm install git+https://git@github.com/thinknathan/tsd-persist-types.git#^0.0.1 --save-dev
```

- Add `tsd-persist` to `types` in `tsconfig.json`

```diff
{
	"compilerOptions": {
		"types": [
+			"tsd-persist",
		],
	}
}
```

- Add `node_modules/@types` to `typeRoots` in `tsconfig.json` if it's not already there

```diff
{
	"compilerOptions": {
		"typeRoots": [
+			"node_modules/@types",
		],
	}
}
```

<p align="center" class="h4">
  TypeScript :heart: Defold
</p>
