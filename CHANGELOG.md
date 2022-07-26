## [1.1.23](https://github.com/Avansai/messages-modules/compare/1.1.22...1.1.23) (2022-12-11)

## [1.1.22](https://github.com/Avansai/messages-modules/compare/1.1.21...1.1.22) (2022-12-04)

## [1.1.21](https://github.com/Avansai/messages-modules/compare/1.1.20...1.1.21) (2022-11-28)

## [1.1.20](https://github.com/Avansai/messages-modules/compare/1.1.19...1.1.20) (2022-11-18)

## [1.1.19](https://github.com/Avansai/messages-modules/compare/1.1.18...1.1.19) (2022-11-13)

## [1.1.18](https://github.com/Avansai/messages-modules/compare/1.1.17...1.1.18) (2022-11-06)

## [1.1.17](https://github.com/Avansai/messages-modules/compare/1.1.16...1.1.17) (2022-10-31)

### Bug Fixes

- fix issue where an unused import could cause build failure ([9630422](https://github.com/Avansai/messages-modules/commit/9630422de02314928dfab3793540e56ab551daaf))

## [1.1.16](https://github.com/Avansai/messages-modules/compare/1.1.15...1.1.16) (2022-10-27)

## [1.1.15](https://github.com/Avansai/messages-modules/compare/1.1.14...1.1.15) (2022-10-20)

### Bug Fixes

- fix issue where using message functions in arrays would cause name collision ([c9dfa2c](https://github.com/Avansai/messages-modules/commit/c9dfa2c50d47fa84215b8818f48022edda071619))

## [1.1.14](https://github.com/Avansai/messages-modules/compare/1.1.13...1.1.14) (2022-10-16)

## [1.1.13](https://github.com/Avansai/messages-modules/compare/1.1.12...1.1.13) (2022-10-09)

## [1.1.12](https://github.com/Avansai/messages-modules/compare/1.1.11...1.1.12) (2022-10-04)

## [1.1.11](https://github.com/Avansai/messages-modules/compare/1.1.10...1.1.11) (2022-10-04)

## [1.1.10](https://github.com/Avansai/messages-modules/compare/1.1.9...1.1.10) (2022-10-04)

## [1.1.9](https://github.com/Avansai/messages-modules/compare/1.1.8...1.1.9) (2022-10-03)

## [1.1.8](https://github.com/Avansai/messages-modules/compare/1.1.7...1.1.8) (2022-09-25)

## [1.1.7](https://github.com/Avansai/messages-modules/compare/1.1.6...1.1.7) (2022-09-15)

## [1.1.6](https://github.com/Avansai/messages-modules/compare/1.1.5...1.1.6) (2022-09-09)

## [1.1.5](https://github.com/Avansai/messages-modules/compare/1.1.4...1.1.5) (2022-08-30)

## [1.1.4](https://github.com/Avansai/messages-modules/compare/1.1.3...1.1.4) (2022-08-23)

## [1.1.3](https://github.com/Avansai/messages-modules/compare/1.1.2...1.1.3) (2022-08-14)

### Bug Fixes

- add missing ESLint `plugin:import/typescript` ([2a07d1c](https://github.com/Avansai/messages-modules/commit/2a07d1ca74531dd35edd198117264ae2be851429))
- remove overly intrusive ESLint rules ([e298a9e](https://github.com/Avansai/messages-modules/commit/e298a9e845fbeb44ee00b54fc58b742f796a4ff8))

## [1.1.2](https://github.com/Avansai/messages-modules/compare/1.1.1...1.1.2) (2022-08-12)

### Bug Fixes

- fix Next.js `ReferenceError` compile errors ([a1a9d9d](https://github.com/Avansai/messages-modules/commit/a1a9d9dae5b1308d97b6c0ee2d499ade2776785f))

## [1.1.1](https://github.com/Avansai/messages-modules/compare/1.1.0...1.1.1) (2022-08-11)

### Bug Fixes

- fix Babel scope tracker errors ([1400526](https://github.com/Avansai/messages-modules/commit/1400526e5c80e67b442845ecfdb538dcaf6afe31))

# [1.1.0](https://github.com/Avansai/messages-modules/compare/1.0.0...1.1.0) (2022-08-11)

### Code Refactoring

- add `eslint-plugin-unicorn` to help increase code quality ([41643ae](https://github.com/Avansai/messages-modules/commit/41643aef87910bd4785925260c44e6615a73716a))

### Features

- add named export support for shared messages ([630f1c1](https://github.com/Avansai/messages-modules/commit/630f1c12edd27682508a97695e18bf7934145727))

### BREAKING CHANGES

- Using the `node:` scheme to better identify Node.js modules requires more recent Node.js versions

# [1.0.0](https://github.com/Avansai/messages-modules/compare/0.0.3...1.0.0) (2022-08-01)

Official stable stable release.

## [0.0.3](https://github.com/Avansai/messages-modules/compare/0.0.2...0.0.3) (2022-07-25)

## 0.0.2 (2022-07-24)

### Bug Fixes

- remove unused dependencies ([0496731](https://github.com/Avansai/messages-modules/commit/04967313806e102dde010af1d8716d952a0d260a))

### Features

- first working Babel plugin ([d58b0d3](https://github.com/Avansai/messages-modules/commit/d58b0d343b2d9d6eaf543378fa2c184bf58e8b3a))
- remove namespace import support to simplify the plugin ([6ab7e3c](https://github.com/Avansai/messages-modules/commit/6ab7e3cbc622bcae5115fd6a5baad8afaa608dc0))

### BREAKING CHANGES

- There was a bug that would have needed to be fixed around namespace imports but since there is no real season to use this, its better to just drop this feature.
