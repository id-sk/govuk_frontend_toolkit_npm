# ID-SK frontend toolkit npm package

This is an npm package for [the ID-SK frontend toolkit][toolkit].
It bundles up the toolkit and publishes [idsk_frontend_toolkit on the npmjs
registry][npmjs] so that you can install it as a dependency in your JavaScript
application.

## Installing

To include the toolkit in your project run:

```
npm install --save idsk_frontend_toolkit
```

This will install the toolkit inside your `node_modules` and will add the
package to your package.json.

## Updating this package

All development of the toolkit should happen [upstream][toolkit] and changes
will then become available in this package.

When master is changed in the upstream repo Travis will [trigger a build][trigger]
of this repository, which will automatically build and publish the module if the
version in `VERSION.txt` is newer than the version published on NPM registry.

## Licence

[MIT License](LICENCE)


[toolkit]: https://github.com/id-sk/idsk_frontend_toolkit
[npmjs]: https://www.npmjs.org/package/idsk_frontend_toolkit
[trigger]: https://github.com/id-sk/idsk_frontend_toolkit/blob/master/trigger.sh
