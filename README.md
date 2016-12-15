# electron-asar-dirname-issue

`__dirname` in unpacked directory points to `app.asar`

## Setup

1. `git clone` this repo
2. `npm i`
3. `npm run pack`
4. `npm start`

## Output

```sh
Running...
dirname in unpacked /path/to/electron-asar-dirname-issue/out/app.asar/unpacked
```

**Expected:** Path should point to `app.asar.unpacked`

## LICENSE

Public domain.
