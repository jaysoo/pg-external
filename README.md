# API demo


Run the build:

```
$ npx nx build
```

And see that `pg` is marked as external.

```
$ cat dist/server/package.json
{
  "name": "server",
  "version": "0.0.0",
  "dependencies": {
    "axios": "^1.0.0",
    "pg": "8.9.0",
    "tslib": "^2.3.0"
  },
  "main": "./main.js"
}
```
