# [@hig/profile-flyout-v2.0.0](https://github.com/Autodesk/hig/compare/@hig/profile-flyout@1.0.1...@hig/profile-flyout@2.0.0) (2019-01-23)


### Bug Fixes

* **package:** update [@hig](https://github.com/hig)/flyout to version 1.0.0 ([12326f0](https://github.com/Autodesk/hig/commit/12326f0))


### Features

* make profile themeable ([4bf3975](https://github.com/Autodesk/hig/commit/4bf3975))


### BREAKING CHANGES

* CSS classnames have been removed
Stylesheet does not need to be imported
@hig/typography is used for the Profile Name and Profile Email

# [@hig/profile-flyout-v1.0.1](https://github.com/Autodesk/hig/compare/@hig/profile-flyout@1.0.0...@hig/profile-flyout@1.0.1) (2019-01-08)


### Bug Fixes

* **package:** update [@hig](https://github.com/hig)/avatar to version 1.0.1 ([4f3382e](https://github.com/Autodesk/hig/commit/4f3382e))
* **package:** update [@hig](https://github.com/hig)/flyout to version 0.8.0 ([37ab319](https://github.com/Autodesk/hig/commit/37ab319))

# [@hig/profile-flyout-v1.0.0](https://github.com/Autodesk/hig/compare/@hig/profile-flyout@0.1.1...@hig/profile-flyout@1.0.0) (2019-01-04)


### Bug Fixes

* **avatar:** add theme knobs in avatar storybook, use only one letter for avatar when size is small, fix js warnings ([4057b51](https://github.com/Autodesk/hig/commit/4057b51))
* **package:** update [@hig](https://github.com/hig)/flyout to version 0.7.0 ([5d0cc55](https://github.com/Autodesk/hig/commit/5d0cc55))
* uses correct font weight and pressed halo color ([0a58054](https://github.com/Autodesk/hig/commit/0a58054))


### Features

* **avatar:** themable avatar ([0fbd821](https://github.com/Autodesk/hig/commit/0fbd821))
* gives buttons intended height ([9358562](https://github.com/Autodesk/hig/commit/9358562))


### BREAKING CHANGES

* **avatar:** The sizes.LARGE_36 size is no longer supported. You can
substitute with sizes.MEDIUM_32 or sizes.LARGE_48. The "large-48" size
is no longer supported. You can substitute it with "large" for 48 pixels
wide or "medium-32" for 32 pixels wide. The previous "large" size is now
48 pixels wide rather than 36 pixels wide.

# [@hig/profile-flyout-v0.1.1](https://github.com/Autodesk/hig/compare/@hig/profile-flyout@0.1.0...@hig/profile-flyout@0.1.1) (2018-10-02)


### Bug Fixes

* top nav profile name needs to be bold ([ebe2d0e](https://github.com/Autodesk/hig/commit/ebe2d0e))

# [@hig/profile-flyout-v0.1.0](https://github.com/Autodesk/hig/compare/@hig/profile-flyout@0.0.0...@hig/profile-flyout@0.1.0) (2018-09-19)


### Bug Fixes

* **bundle:** Fix package bundles ([a1b479d](https://github.com/Autodesk/hig/commit/a1b479d))
* **bundle:** include dependency CSS ([f5a4a62](https://github.com/Autodesk/hig/commit/f5a4a62))


### Features

* **profile-flyout:** Add ProfileFlyout placeholders ([5ebad57](https://github.com/Autodesk/hig/commit/5ebad57))
* rewrite `ProfileFlyout` ([d4ba4c1](https://github.com/Autodesk/hig/commit/d4ba4c1))
