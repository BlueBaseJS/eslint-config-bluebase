<div align="center">
	<img width=125 height=125 src="logo.png">
  <h1>
		BlueBase Eslint Config
	</h1>
  <p>An Eslint Configuration for BlueBase projects</p>
</div>

<hr />


### Setup

- Install this package
```
yarn add @bluebase/eslint-config-bluebase
```
- Create a `.eslintrc` file on the root of your project with the following content
```
{
    "extends": [
    	"@bluebase/eslint-config-bluebase/eslint.js"
    ]
}
```
- Add the following lines to `scripts` in `package.json`
```
"lint" : "eslint src --ext=jsx,ts,tsx",
"fix:lint" : "eslint src --ext=jsx,ts,tsx --fix"
```

- Run lint 
```
yarn lint
```

- Fix lint 
```
yarn fix:lint
```
