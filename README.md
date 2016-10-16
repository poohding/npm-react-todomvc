# npm-react-todomvc
React TodoMVC with npm scripts


## List of available tasks
### `clean`
`rimraf dist/`

Clean existing dist folder

### `npm run build`
`npm run clean && npm test && npm run build:js && npm run build:css && npm run build:html`

Production build

### `npm run dev`
`npm run clean && npm run dev:js && npm run dev:css && npm run dev:html`

Development build

### `npm start`
`npm run watch:css & npm run watch:js && npm run dev`

Watch

### `npm test`
`eslint & karma start`

Linting &amp; Testing
