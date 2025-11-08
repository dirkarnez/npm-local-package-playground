npm-local-package-playground
============================
### Tutorials
[node.js - Local dependency in package.json - Stack Overflow](https://stackoverflow.com/questions/14381898/local-dependency-in-package-json)

### Notes
- `npm link` is not really needed because local package is better than symlink
- use [workspaces | npm Docs](https://docs.npmjs.com/cli/v7/using-npm/workspaces)

### Steps
1. In local package, work as normal, **also build it** + `npm install` to get package-lock.json
2. In consummer package: `npm install file:./packages/bar`
