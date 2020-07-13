## minimal:
> chrome manifest version 2.0

- `manifest.json`


## npm requirements:
> `--save-dev` unless noted otherwise
> `npm install --production`

- `crx-hotreload@1.0.4`
> extremely tiny script to help with hot reloading the minimal plugin structure
> uses timestamps of files to refresh the browser and plugin without manually reloading
> reloads `manifest.json` as well as plugin source files.

- `webpack@4.43.0`
> needed for bundling all the resources into a single production file.
> code-splitting, tree shaking, minification, optimization, and obfuscation.
> helpful for working with saas, frameworks (vue.js), more complex app development




## folder structure
* `/build`
> deliverable binary for chrome `.crx`

* `/src`
 - `/css`
 - `/html`
 - `/images`
 - `/js`
