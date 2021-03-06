```
next-updater - Dependable and safe automatic dependency updater for Nodejs packages
 version: 0.9.1
 author: Gleb Bahmutov <gleb.bahmutov@gmail.com>
 more info at: https://github.com/bahmutov/next-updater

Options:
  --version, -v   show version and exit                              [default: false]
  --push, -p      push changes (if any) to remote origin             [string]  [default: true]
  --repo, -r      <github username/repo>                             [default: null]
  --config, -c    JSON config filename                               [default: null]
  --user, -u      fetch list of repos for this github username       [default: null]
  --sort, -s      sort repos (listed, reverse, asc, desc)            [string]  [default: undefined]
  --clean         delete temp folder after finished                  [default: false]
  --allow         allow major / minor / patch updates                [default: "major"]
  --tag, -t       tag changed code with new patch version            [default: false]
  --publish       publish to NPM (if updated and has package.json)   [default: false]
  --npm-user, -n  update all NPM published repos for the given user  [default: null]
  -N              Limit update to first N sorted repos               [default: 10000]
```
