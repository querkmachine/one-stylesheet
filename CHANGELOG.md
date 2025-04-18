# Changelog

Specific versions can be installed via npm by running the install command with a [tag number](https://github.com/querkmachine/one-stylesheet/tags) appended, e.g. `npm install querkmachine/one-stylesheet#1.0.0`.

## 2.0.0 (2025-04-18)

Updates many visual aspects to align with changes to beeps.website.

- Updated spacing properties.
- Updated light mode colours.
- Updated link styles to resolve an issue with some forced colours users.
- Updated the design of `mark` elements.
- Updated the design of `code` and code blocks.
- Added new CSS properties:
  - `--color-surface` for offsetting areas from the canvas colour.
  - `--color-text-subtle` for secondary text.
  - `--color-text-accent` for emphasised text.
  - `--color-link-hover` for hovered links.
  - `--color-link-visited` for visited links (currently the same as hovered links).
- **Breaking:** Removed `--color-accent`, `--color-accent-alt`, `--color-furniture-alt`, `--color-link-underline`, `--color-link-underline-hover`, and `--color-link-underline-visited` CSS properties.

## 1.1.0 (2024-07-07)

- Added new styles for `abbr` elements.
- Added top margin to `h1` elements.
- Added styles for `q` elements.
- Improved styles for multiple paragraphs within `blockquote`s.
- Changed the highlight colour used by `mark` to have higher contrast.
- Reduced the top and bottom padding on the body.

## 1.0.0 (2024-06-16)

- Initial release.
