https://github.com/rstackjs/ts-checker-rspack-plugin/issues/59

# Reproduction Steps

1. Start dev server `pnpm dev`
2. Open `App.tsx` and add `console.log('12)`
3. observe dev server errors as expected
4. fix the syntax error to `console.log('12')`
5. watch server never recovers
