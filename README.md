# NPM Scripts Bundler 📦
Original repo by deliciousbrains, forked by yours truly.

## Changes
- Uses the `concurrently` package instead of `npm-run-all`.
- Utilizes `uglify-es` for ES6 support as opposed to `uglify-js`.
    - Adds the `--mangle toplevel` flag to the `uglify-es` npm script.
- Handles `.css` files in addition to `.scss` files

... and more to come 🤙

## Up and Running 🏃‍♀️
1. To get up and running install the required packages via npm, `npm i`
2. Run `npm run dev` to watch for `*.scss` or `*.js` changes
3. Run `npm run build` to output concatenated and minified files to the `dist/` folder