This package provides the type definitions for the mu package used in the [mu-javascript-template](https://github.com/mu-semtech/mu-javascript-template).

> [!IMPORTANT]
> As the mu package is only available internally in the template and it shares its name with a package that is already available on npm, we can't just make these types available as `@types/mu`.

## Installation

These types can be installed regularly like any other npm package, e.g. add this to your package.json:

```json
{
  "devDependencies": {
    "mu-types": "git+https://github.com/rahien/mu-types.git"
  }
}
```

Then, you need to add this to your `tsconfig.json` file (create it if it doesn't exist yet):

```json
{
  "compilerOptions": {
    "types": ["mu-types"]
  }
}
```
