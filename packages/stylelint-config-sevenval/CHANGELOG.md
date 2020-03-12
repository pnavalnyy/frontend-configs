# Changelog

## 3.0.1

- Upgraded all dependencies to their latest possible version while maintaining nodeJs 8 compatibility
  - `stylelint-config-standard` upgraded from ^18.2.0 to ^20.0.0
  - `stylelint` upgraded from ^10.1.0 to ^12.0.1

## 3.0.0

- Upgraded dependencies with major version increases
  - `stylelint` from 9 to 10

## 2.0.2

- Remove code-formatting rules to be compatible with `prettier`

## 2.0.1

- Upgrade dependencies
- Remove `unit-blacklist` rule.

## 2.0.0

- Upgrade all dependencies (major). Fixes semver issue with `postcss-selector-parser`

## 1.4.0

- Warn when using `px` instead of `rem` or `em`
- Limit nesting to a depth of `4`

## 1.3.3

- Upgrade [stylelint](https://github.com/stylelint/stylelint) which renamed a few ruless
- Upgrade all dependencies
- Test on both node 6 and 7
- Add Sass `@content` to at-rule exceptions

## 1.3.2

- Add Sass `@function` and `@return` to at-rule exceptions

## 1.3.1

- Allow scss and css-modules in the same file

## 1.3.0

- Add support for CSS-Modules

## 1.2.1

- Complete repo transfer to sevenval organization

## 1.2.0

- Support sass conditionals in one line

```scss
@if $a {
  color: red;
} @else {
  color: blue;
}
```

## 1.1.0

- Remove selector depth limits. There is no way that would go well with parsing projects
- Disable "declaration-empty-line-before" rule. We don't have an empty line after `@extend`

## 1.0.0

- Initial Release
