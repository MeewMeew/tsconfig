# tsconfig

> Shared [TypeScript config](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html) for my projects

## Install

```sh
npm install --save-dev @meewmeew/tsconfig
```


```sh
yarn add --dev @meewmeew/tsconfig
```

*This config requires TypeScript 4.7 or later.*

## Usage

`tsconfig.json`

```json
{
	"extends": "@meewmeew/tsconfig",
	"compilerOptions": {
		"outDir": "build"
	}
}
```

When you are targeting a higher version of Node.js, check the relevant ECMAScript version and add it as `target`:

```json
{
	"extends": "@meewmeew/tsconfig",
	"compilerOptions": {
		"outDir": "build",
		"target": "ES2021"
	}
}
```