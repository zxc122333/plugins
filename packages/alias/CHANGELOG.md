# @rollup/plugin-alias ChangeLog

## v3.0.1

_2020-02-01_

### Updates

- docs: Fix reference to plugin-node-resolve (#175)
- chore: update dependencies (bcb53d8)
- chore: update dependencies (e36540f)
- chore: fix minor linting issue (a695579)

## 3.0.0

### Breaking Changes

- feat(alias): built-in resolving algorithm is replaced in favor of Rollup's `this.resolve()` (#34)

## 2.2.0

_2019-10-21_

- Support resolving `index.js` files in directories ([#64](https://github.com/rollup/rollup-plugin-alias/pull/64) by @jerriclynsjohn)

## 2.1.0

_2019-10-18_

- Add support for object syntax ([#61](https://github.com/rollup/rollup-plugin-alias/pull/61) by @Andarist)

## 2.0.1

_2019-09-27_

- Update dependencies ([#59](https://github.com/rollup/rollup-plugin-alias/pull/59) by @lukastaegert)
- Make volume letter regexp case independent ([#57](https://github.com/rollup/rollup-plugin-alias/pull/57) by @MarekLacoAXA)

## 2.0.0

_2019-08-22_

- Add RegExp support and strict order of entries ([#53](https://github.com/rollup/rollup-plugin-alias/pull/53) by @thiscantbeserious)

### Breaking Changes

Aliases always need to be provided as an array, see #53

## 1.5.2

- Update dependencies

## 1.5.1

- Update tests for Rollup@1.0 compatibility and tests ([#48](https://github.com/rollup/rollup-plugin-alias/pull/48))

## 1.4.0

- Various Windows fixes ([#22](https://github.com/rollup/rollup-plugin-alias/pull/22))
- Don't try to alias entry file ([#29](https://github.com/rollup/rollup-plugin-alias/pull/29))

## 1.3.0

- Start maintaining a changelog
- Fix `isFilePath` on Windows ([#3](https://github.com/rollup/rollup-plugin-alias/issues/3))
