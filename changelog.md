# Changelog

All notable changes to this project will be documented in this file.

## Unreleased

## [0.0.8](https://github.com/silencesys/silent-sass/compare/b4bf7280f3c5ccce4d6719e83abeb79fd2ff6068...812aeb07f5c99567532341d00be63b5a7f5771e3) - 10/10/2017
### Changed
+ Mixin `response-to()` is renamed to `respond-to()`.
+ From mixins `grid()`, `grid-column()`, `grid-row()` were removed lines with prefix -ms, because I found almost impossilbe
to handle grids in Microsoft browsers same way as modern browsers. So grids in Microsoft browsers should be handled
different way.

### Removed
+ Mixin `baseline-grid()` - it never worked.
+ Mixin `font-rhythm()` and `set-font-size()` mixin should be used instead.