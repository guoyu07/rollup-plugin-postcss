## [Version 1.4.0](https://github.com/egoist/rollup-plugin-postcss/releases/tag/v1.4.0) (2018-3-18)

### New features

- automatically css modules, closes [#87](https://github.com/egoist/rollup-plugin-postcss/issues/87): [`707ca3e`](https://github.com/egoist/rollup-plugin-postcss/commit/707ca3e)

[...full changes](https://github.com/egoist/rollup-plugin-postcss/compare/v1.3.4...v1.4.0)

## [Version 1.3.4](https://github.com/egoist/rollup-plugin-postcss/releases/tag/v1.3.4) (2018-3-15)

### Bug fixes

- only return sourceMap if necessary: [`88f7aff`](https://github.com/egoist/rollup-plugin-postcss/commit/88f7aff)
- Replace localRequire with the `import-cwd` package: [`df195e2`](https://github.com/egoist/rollup-plugin-postcss/commit/df195e2) ([#85](https://github.com/egoist/rollup-plugin-postcss/issues/85))

[...full changes](https://github.com/egoist/rollup-plugin-postcss/compare/v1.3.3...v1.3.4)

## [Version 1.3.3](https://github.com/egoist/rollup-plugin-postcss/releases/tag/v1.3.3) (2018-3-5)

### Bug fixes

- skip logging when namedExports is a function, closed [#82](https://github.com/egoist/rollup-plugin-postcss/issues/82): [`3163614`](https://github.com/egoist/rollup-plugin-postcss/commit/3163614)

[...full changes](https://github.com/egoist/rollup-plugin-postcss/compare/v1.3.2...v1.3.3)

## [Version 1.3.2](https://github.com/egoist/rollup-plugin-postcss/releases/tag/v1.3.2) (2018-3-2)

### Bug fixes

- fix styleInject path on windows: [`db7db7a`](https://github.com/egoist/rollup-plugin-postcss/commit/db7db7a) ([#81](https://github.com/egoist/rollup-plugin-postcss/issues/81))

[...full changes](https://github.com/egoist/rollup-plugin-postcss/compare/v1.3.1...v1.3.2)

## [Version 1.3.1](https://github.com/egoist/rollup-plugin-postcss/releases/tag/v1.3.1) (2018-2-27)

### Bug fixes

- fix sass importer, closed [#78](https://github.com/egoist/rollup-plugin-postcss/issues/78): [`e7b435d`](https://github.com/egoist/rollup-plugin-postcss/commit/e7b435d)

[...full changes](https://github.com/egoist/rollup-plugin-postcss/compare/v1.3.0...v1.3.1)

## [Version 1.3.0](https://github.com/egoist/rollup-plugin-postcss/releases/tag/v1.3.0) (2018-2-26)

### New features

- Use ~ to resolve node_modules in Sass: [`913c2db`](https://github.com/egoist/rollup-plugin-postcss/commit/913c2db) ([#77](https://github.com/egoist/rollup-plugin-postcss/issues/77))

[...full changes](https://github.com/egoist/rollup-plugin-postcss/compare/v1.2.9...v1.3.0)

## [Version 1.2.9](https://github.com/egoist/rollup-plugin-postcss/releases/tag/v1.2.9) (2018-2-22)

### Bug fixes

- inject style-inject as a module: [`beef7c5`](https://github.com/egoist/rollup-plugin-postcss/commit/beef7c5)
- pass filename to less: [`c8ed3e2`](https://github.com/egoist/rollup-plugin-postcss/commit/c8ed3e2) ([#74](https://github.com/egoist/rollup-plugin-postcss/issues/74))
- use relative path in less sourcemap: [`bf33792`](https://github.com/egoist/rollup-plugin-postcss/commit/bf33792)
- pass options to less and stylus loaders: [`71a2265`](https://github.com/egoist/rollup-plugin-postcss/commit/71a2265)

[...full changes](https://github.com/egoist/rollup-plugin-postcss/compare/v1.2.8...v1.2.9)

## [Version 1.2.8](https://github.com/egoist/rollup-plugin-postcss/releases/tag/v1.2.8) (2018-1-30)

### Bug fixes

- allow to control how exported named is generated, fixed [#64](https://github.com/egoist/rollup-plugin-postcss/issues/64): [`3b6d7cb`](https://github.com/egoist/rollup-plugin-postcss/commit/3b6d7cb)

[...full changes](https://github.com/egoist/rollup-plugin-postcss/compare/v1.2.7...v1.2.8)

## [Version 1.2.6](https://github.com/egoist/rollup-plugin-postcss/releases/tag/v1.2.6) (2018-1-24)

### Bug fixes

- Fix issues with using postcss-import plugin and postcss-modules plugin: [`0897815`](https://github.com/egoist/rollup-plugin-postcss/commit/0897815) ([#62](https://github.com/egoist/rollup-plugin-postcss/issues/62))

[...full changes](https://github.com/egoist/rollup-plugin-postcss/compare/v1.2.4...v1.2.6)

## [Version 1.2.5](https://github.com/egoist/rollup-plugin-postcss/releases/tag/v1.2.5) (2018-1-17)

### Bug fixes

- fix for..of transpilation error: [`0fe23ad`](https://github.com/egoist/rollup-plugin-postcss/commit/0fe23ad)

[...full changes](https://github.com/egoist/rollup-plugin-postcss/compare/v1.2.4...v1.2.5)

## [Version 1.2.3](https://github.com/egoist/rollup-plugin-postcss/releases/tag/v1.2.3) (2018-1-16)

### Bug fixes

- normalize extracted path: [`14e5df0`](https://github.com/egoist/rollup-plugin-postcss/commit/14e5df0)

[...full changes](https://github.com/egoist/rollup-plugin-postcss/compare/v1.2.2...v1.2.3)

## [Version 1.2.2](https://github.com/egoist/rollup-plugin-postcss/releases/tag/v1.2.2) (2018-1-16)

### Bug fixes

- support custom path for extracted css file, fixed [#60](https://github.com/egoist/rollup-plugin-postcss/issues/60): [`6eb0cc5`](https://github.com/egoist/rollup-plugin-postcss/commit/6eb0cc5)

[...full changes](https://github.com/egoist/rollup-plugin-postcss/compare/v1.2.1...v1.2.2)

## [Version 1.2.1](https://github.com/egoist/rollup-plugin-postcss/releases/tag/v1.2.1) (2018-1-14)

### Bug fixes

- update bili to fix a transpilation bug: [`5e4c8dd`](https://github.com/egoist/rollup-plugin-postcss/commit/5e4c8dd)

[...full changes](https://github.com/egoist/rollup-plugin-postcss/compare/v1.2.0...v1.2.1)

## [Version 1.2.0](https://github.com/egoist/rollup-plugin-postcss/releases/tag/v1.2.0) (2018-1-14)

### New features

- add onExtract option: [`25360d5`](https://github.com/egoist/rollup-plugin-postcss/commit/25360d5)

### Bug fixes

- tweaks: [`9297035`](https://github.com/egoist/rollup-plugin-postcss/commit/9297035)

[...full changes](https://github.com/egoist/rollup-plugin-postcss/compare/v1.1.0...v1.2.0)

## [Version 1.1.0](https://github.com/egoist/rollup-plugin-postcss/releases/tag/v1.1.0) (2018-1-13)

### New features

- support stylus/less and enable loaders by default: [`977c666`](https://github.com/egoist/rollup-plugin-postcss/commit/977c666)

### Bug fixes

- tweaks: [`0565a37`](https://github.com/egoist/rollup-plugin-postcss/commit/0565a37)
- no need to warn about sourcemap: [`19cbe01`](https://github.com/egoist/rollup-plugin-postcss/commit/19cbe01)

[...full changes](https://github.com/egoist/rollup-plugin-postcss/compare/v1.0.5...v1.1.0)

## [Version 1.0.5](https://github.com/egoist/rollup-plugin-postcss/releases/tag/v1.0.5) (2018-1-12)

### Bug fixes

- fix inferOption [#54](https://github.com/egoist/rollup-plugin-postcss/issues/54): [`10d7523`](https://github.com/egoist/rollup-plugin-postcss/commit/10d7523)

[...full changes](https://github.com/egoist/rollup-plugin-postcss/compare/v1.0.4...v1.0.5)

## [Version 1.0.4](https://github.com/egoist/rollup-plugin-postcss/releases/tag/v1.0.4) (2018-1-11)

### Bug fixes

- escape $ in replace argument, fixed [#58](https://github.com/egoist/rollup-plugin-postcss/issues/58): [`924513e`](https://github.com/egoist/rollup-plugin-postcss/commit/924513e)

[...full changes](https://github.com/egoist/rollup-plugin-postcss/compare/v1.0.3...v1.0.4)

## [Version 1.0.3](https://github.com/egoist/rollup-plugin-postcss/releases/tag/v1.0.3) (2018-1-11)

### Bug fixes

- fix postcss options, closed [#57](https://github.com/egoist/rollup-plugin-postcss/issues/57): [`92f1394`](https://github.com/egoist/rollup-plugin-postcss/commit/92f1394)

[...full changes](https://github.com/egoist/rollup-plugin-postcss/compare/v1.0.2...v1.0.3)

## [Version 1.0.2](https://github.com/egoist/rollup-plugin-postcss/releases/tag/v1.0.2) (2018-1-10)

### Bug fixes

- actually skip loader if didn't pass `test`: [`4c3688d`](https://github.com/egoist/rollup-plugin-postcss/commit/4c3688d)

[...full changes](https://github.com/egoist/rollup-plugin-postcss/compare/v1.0.1...v1.0.2)

## [Version 1.0.1](https://github.com/egoist/rollup-plugin-postcss/releases/tag/v1.0.1) (2018-1-10)

### Bug fixes

- reintroduce namedExports: [`3381db8`](https://github.com/egoist/rollup-plugin-postcss/commit/3381db8)

[...full changes](https://github.com/egoist/rollup-plugin-postcss/compare/v1.0.0...v1.0.1)


---

Generated by [changelog.md](https://github.com/egoist/changelog.md)
