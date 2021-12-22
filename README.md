# rimraf error

```txt
λ npx rimraf node_modules
The system cannot find the path specified.
```

Steps to repro

1. clone repo
1. run `yarn`
1. run `npx rimraf node_modules`

May be specific to version of Node installed. It happens with node v16.13.1 but does not happen with v14.17.3.
