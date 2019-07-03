# eslint-config-derniercri-typescript

Install the package:

```bash
yarn add -D git+https://github.com/derniercri/eslint-config-derniercri-typescript.git
```

Create or edit a `.eslintrc` file at project's root :

```json
{
  "extends": [
    "eslint-config-derniercri-typescript"
  ]
}
```

Add the following script to your `package.json`

```json
"lint": "tslint 'src/**/*.{t,j}s{,x}'"
```

And voilà !

Check the **sample** folder of this repository for a concrete example.
