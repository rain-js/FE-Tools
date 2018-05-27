# FE-Tools
> Learn FE Tools


### node-sass
1. Install
	```
	npm init
	npm install node-sass
	```

2. Usage
	```
	./node_modules/.bin/node-sass src/style.scss dist/style.css
	```

### Babel
1. Install
	```
	npm init
	npm install --save-dev babel-cli
	npm install babel-preset-env --save-dev
	```

2. Usage
	```
	npm scripts: babel src -d dist -w
	npm run build	
	```