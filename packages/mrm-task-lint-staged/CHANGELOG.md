# Change Log

All notable changes to this project will be documented in this file. See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## 7.1.14 (2023-03-10)

**Note:** Version bump only for package mrm-task-lint-staged

## 7.1.13 (2022-10-19)

**Note:** Version bump only for package mrm-task-lint-staged

## 7.1.12 (2022-10-19)

**Note:** Version bump only for package mrm-task-lint-staged

## 7.1.11 (2022-10-19)

**Note:** Version bump only for package mrm-task-lint-staged

## 7.1.10 (2022-10-18)

**Note:** Version bump only for package mrm-task-lint-staged

## 7.1.9 (2022-10-18)

**Note:** Version bump only for package mrm-task-lint-staged

## 7.1.8 (2022-10-17)

**Note:** Version bump only for package mrm-task-lint-staged

## 7.1.7 (2022-10-16)

**Note:** Version bump only for package mrm-task-lint-staged

## 7.1.6 (2022-09-15)

**Note:** Version bump only for package mrm-task-lint-staged

## 7.1.5 (2022-09-15)

### Bug Fixes

- Pass correct parameters to pnpm ([#235](https://github.com/sapegin/mrm/issues/235)) ([92cb61c](https://github.com/sapegin/mrm/commit/92cb61c03c02559269cfaadaa391a069ef9add08))

## 7.1.4 (2022-09-15)

**Note:** Version bump only for package mrm-task-lint-staged

## 7.1.3 (2022-09-15)

**Note:** Version bump only for package mrm-task-lint-staged

## 7.1.2 (2022-09-15)

**Note:** Version bump only for package mrm-task-lint-staged

## 7.1.1 (2022-09-15)

**Note:** Version bump only for package mrm-task-lint-staged

# 7.1.0 (2022-08-23)

### Features

- Aliases could reference other aliases ([#104](https://github.com/sapegin/mrm/issues/104)) ([4c718f8](https://github.com/sapegin/mrm/commit/4c718f80029a218357204fd788c0bccdf99b7d67))

# 7.0.0 (2022-03-22)

### Features

- **lint-staged:** Husky upgrade v6 to v7 ([#206](https://github.com/sapegin/mrm/issues/206)) ([87779e8](https://github.com/sapegin/mrm/commit/87779e891efbd61ec10b59f7c41ac66b4263d6ce)), closes [#205](https://github.com/sapegin/mrm/issues/205) [#192](https://github.com/sapegin/mrm/issues/192)

### BREAKING CHANGES

- **lint-staged:** Node 10 support was dropped from Husky v7

## 6.0.8 (2021-10-14)

**Note:** Version bump only for package mrm-task-lint-staged

## 6.0.7 (2021-09-18)

**Note:** Version bump only for package mrm-task-lint-staged

## 6.0.6 (2021-08-03)

**Note:** Version bump only for package mrm-task-lint-staged

## 6.0.5 (2021-08-03)

### Bug Fixes

- **core:** Fix types of yaml method ([#190](https://github.com/sapegin/mrm/issues/190)) ([7cdd216](https://github.com/sapegin/mrm/commit/7cdd216681155e44a3d17f4d734a2d6f91fede4c))

## 6.0.4 (2021-08-02)

### Bug Fixes

- **eslint:** Add missing lodash dependency ([#164](https://github.com/sapegin/mrm/issues/164)) ([cea24d8](https://github.com/sapegin/mrm/commit/cea24d80d031c835519db595a3da6a16556be28f))

## 6.0.3 (2021-07-21)

**Note:** Version bump only for package mrm-task-lint-staged

## 6.0.2 (2021-07-21)

**Note:** Version bump only for package mrm-task-lint-staged

## [6.0.1](https://github.com/sapegin/mrm/compare/mrm-task-lint-staged@6.0.0...mrm-task-lint-staged@6.0.1) (2021-07-21)

**Note:** Version bump only for package mrm-task-lint-staged

# [6.0.0](https://github.com/sapegin/mrm/compare/mrm-task-lint-staged@5.0.0...mrm-task-lint-staged@6.0.0) (2021-04-07)

### Features

- Increase supported node version from 8 to 10 ([#138](https://github.com/sapegin/mrm/issues/138)) ([224c673](https://github.com/sapegin/mrm/commit/224c67332ee71b9e275dbea1435cd9088852ff6f))

### BREAKING CHANGES

- Node 8 or 9 are no longer supported, the minimum supported version is now 10.13.

# [5.0.0](https://github.com/sapegin/mrm/compare/mrm-task-lint-staged@4.0.0...mrm-task-lint-staged@5.0.0) (2021-04-01)

### Features

- **lint-staged:** Use husky 6 ([#152](https://github.com/sapegin/mrm/issues/152)) ([133fe08](https://github.com/sapegin/mrm/commit/133fe08b0895b0c994c55d39e0f43af0672fe1f9))

### BREAKING CHANGES

- **lint-staged:** The lint-staged task will migrate simple-git-hooks back to husky 6, the existing simple-git-hooks dependency will be removed.

# [4.0.0](https://github.com/sapegin/mrm/compare/mrm-task-lint-staged@3.1.0...mrm-task-lint-staged@4.0.0) (2021-03-22)

### Features

- Replace husky with simple-git-hooks ([#149](https://github.com/sapegin/mrm/issues/149)) ([8ecd2ce](https://github.com/sapegin/mrm/commit/8ecd2ce0816fb06c395276250fa85dea6f93686d))

### BREAKING CHANGES

- The lint-staged task will migrate `husky` to `simple-git-hooks`, the existing `husky` dependency will be removed.

# [3.1.0](https://github.com/sapegin/mrm/compare/mrm-task-lint-staged@3.0.15...mrm-task-lint-staged@3.1.0) (2021-02-25)

### Features

- Add more fields to package.json ([#134](https://github.com/sapegin/mrm/issues/134)) ([d80840a](https://github.com/sapegin/mrm/commit/d80840a5e771976ef38cdf8a3b535a412e1097f6))

## [3.0.15](https://github.com/sapegin/mrm/compare/mrm-task-lint-staged@3.0.14...mrm-task-lint-staged@3.0.15) (2021-02-20)

### Bug Fixes

- Fix broken lint-staged action by explicitly pining Husky to 4.x ([#146](https://github.com/sapegin/mrm/issues/146)) ([29d2194](https://github.com/sapegin/mrm/commit/29d2194d46c4160d942f559c8511cfbb8b52704e)), closes [#145](https://github.com/sapegin/mrm/issues/145)

## [3.0.14](https://github.com/sapegin/mrm/compare/mrm-task-lint-staged@3.0.13...mrm-task-lint-staged@3.0.14) (2021-02-09)

**Note:** Version bump only for package mrm-task-lint-staged

## [3.0.13](https://github.com/sapegin/mrm/compare/mrm-task-lint-staged@3.0.12...mrm-task-lint-staged@3.0.13) (2021-02-08)

**Note:** Version bump only for package mrm-task-lint-staged

## [3.0.12](https://github.com/sapegin/mrm/compare/mrm-task-lint-staged@3.0.11...mrm-task-lint-staged@3.0.12) (2021-02-03)

**Note:** Version bump only for package mrm-task-lint-staged

## [3.0.11](https://github.com/sapegin/mrm/compare/mrm-task-lint-staged@3.0.10...mrm-task-lint-staged@3.0.11) (2020-11-04)

**Note:** Version bump only for package mrm-task-lint-staged

## [3.0.10](https://github.com/sapegin/mrm/compare/mrm-task-lint-staged@3.0.9...mrm-task-lint-staged@3.0.10) (2020-10-27)

**Note:** Version bump only for package mrm-task-lint-staged

## [3.0.9](https://github.com/sapegin/mrm/compare/mrm-task-lint-staged@3.0.8...mrm-task-lint-staged@3.0.9) (2020-10-27)

**Note:** Version bump only for package mrm-task-lint-staged

## [3.0.8](https://github.com/sapegin/mrm/compare/mrm-task-lint-staged@3.0.7...mrm-task-lint-staged@3.0.8) (2020-10-27)

**Note:** Version bump only for package mrm-task-lint-staged

## [3.0.7](https://github.com/sapegin/mrm/compare/mrm-task-lint-staged@3.0.6...mrm-task-lint-staged@3.0.7) (2020-10-26)

**Note:** Version bump only for package mrm-task-lint-staged

## [3.0.6](https://github.com/sapegin/mrm/compare/mrm-task-lint-staged@3.0.5...mrm-task-lint-staged@3.0.6) (2020-08-19)

**Note:** Version bump only for package mrm-task-lint-staged

## [3.0.5](https://github.com/sapegin/mrm/compare/mrm-task-lint-staged@3.0.4...mrm-task-lint-staged@3.0.5) (2020-06-18)

### Bug Fixes

- Migrate to the new parameters API ([fcc2d61](https://github.com/sapegin/mrm/commit/fcc2d61be7ec720b0cd4c45e3cb65c6f543a45fb))

## [3.0.4](https://github.com/sapegin/mrm/compare/mrm-task-lint-staged@3.0.3...mrm-task-lint-staged@3.0.4) (2020-06-08)

**Note:** Version bump only for package mrm-task-lint-staged

## [3.0.3](https://github.com/sapegin/mrm/compare/mrm-task-lint-staged@3.0.2...mrm-task-lint-staged@3.0.3) (2020-04-07)

**Note:** Version bump only for package mrm-task-lint-staged

## [3.0.2](https://github.com/sapegin/mrm/compare/mrm-task-lint-staged@3.0.1...mrm-task-lint-staged@3.0.2) (2020-03-20)

**Note:** Version bump only for package mrm-task-lint-staged

## 3.0.1 (2020-01-27)

**Note:** Version bump only for package mrm-task-lint-staged
