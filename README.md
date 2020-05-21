# preact-cli-bug-bootstrap-inline-css

- `npm run build`
- `build/index.html` will include a [print-only style](https://github.com/twbs/bootstrap/blob/v4.5.0/dist/css/bootstrap.css#L10241-L10243) from Bootstrap: `body { min-width: 992px !important }`
- The (formatted) styles from my build output are in this [gist](https://gist.github.com/maxfriedrich/bfddaebaba82f20f7350fbb530aca66e)
