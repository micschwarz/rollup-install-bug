# Rollup Repo

## Expected

1. `npm i`
2. `npm run build`
   -> Works

## Actual

1. `npm i`
2. `npm run build`
   -> Fails with `Cannot find module @rollup/rollup-darwin-arm64`

## Fix (in this case)

- Pin roolup version to `4.28.0` in `package.json`
