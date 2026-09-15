## [1.0.2](https://github.com/marslo/ifonts-jenkins/compare/v1.0.1...v1.0.2) (2026-09-15)

### Others

* **console-output**, **node-info**: add light and smaller font for `pipeline-new-node` in console output; using auto-width for build-name in Build History ([02930c0](https://github.com/marslo/ifonts-jenkins/commit/02930c08d5aa8c9495c24c27082f3e173c3be9ef))

## [1.0.1](https://github.com/marslo/ifonts-jenkins/compare/v1.0.0...v1.0.1) (2026-09-11)

### Bug Fixes

* **scope**: stop the style loading site-wide ([264c2de](https://github.com/marslo/ifonts-jenkins/commit/264c2ded2849ab48543fd323821abf6df6983346))
  - move top-level @font-face and :root into the @-moz-document block so the style no longer injects a global section on every site
  - drop three unused google-fonts @import links


### Others

* **BlexMonoLig**: using `"BlexMonoLig Nerd Font Mono"` as default mono font ([b959d6e](https://github.com/marslo/ifonts-jenkins/commit/b959d6e5d74f7a3a805ac81b1ac8dee582c5f51a))

## 1.0.0 (2026-09-11)

### Features

* **ifonts-jenkins**: split jenkins-dedicated userstyle out of ifonts with ci and lint/release tooling ([0867e95](https://github.com/marslo/ifonts-jenkins/commit/0867e952140a3a47a4881e02fa34aa02caee4abf))
  - add ifonts-jenkins.user.css: jenkins controller font userstyle split from the combined ifonts style
  - add README with install and font-download notes
  - add pre-commit CI workflow under .github/workflows
  - add stylelint, semantic-release, pre-commit, and typos configs

  Split from marslo/ifonts@f52f9c8fed6a22b62fbae1eb9f76bf9489ba90e0 (tag v4.1.9).

  Split-from: https://github.com/marslo/ifonts/blob/f52f9c8fed6a22b62fbae1eb9f76bf9489ba90e0/ifonts.user.css
  Split-from-tag: https://github.com/marslo/ifonts/releases/tag/v4.1.9

* Initial commit ([12e4527](https://github.com/marslo/ifonts-jenkins/commit/12e452728ce52cc7dbb959eca72c99c28c718576))
