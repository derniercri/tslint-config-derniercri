# tslint-config-derniercri

Install the package:

```bash
yarn add git+https://github.com/derniercri/tslint-config-derniercri.git
```

Create or edit a `tslint.json` file at project's root :

```json
{
  "extends": [
    "tslint-config-derniercri"
  ]
}
```

Add the following script to your `package.json`

```json
"lint": "tslint 'src/**/*.ts{,x}'"
```

And voilà !

Check the **sample** folder of this repository for a concrete example.
