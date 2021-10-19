# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.0] - 2021-10-19
### Changed
- Migrated from @import rule to @use / @forward (using Sass migrator).
- Placed style of "_fonctionnements", "_hero", "_restaurants" in "_home.scss".
- Placed style of menu header in "_menu-header.scss".

## [0.3.9] - 2021-10-19
### Added
- NEW DEPENDENCIES : "autoprefixer", "postcss", "postcss-cli".
- Cross-browser compatibility (autoprefixer).
- Compiled css with "compressed" option.
- Margin top applied to menu item elements.
- Padding applied to menu text.
- Font variables.

## [0.3.8] - 2021-10-18
### Added
- Badges on the README.
- Pointer cursor on hearts.
- mailto link on footer contact.


## [0.3.7] - 2021-10-18
### Fixed
- Adjusting footer on mobile and tablet versions.
- Z index of loading screen.


## [0.3.6] - 2021-10-18
### Added
- box-shadow and hover effects on various elements (buttons, cards, items...)
- Hover effect on "fonctionnement" items.

### Fixed
- Adjusting prince position on menu item cards.
- Adjusting "Nouveau" rectangle on restaurant selection.
- Adjusting font sizes.

### Changed
- Using Font Awesome icons for "Fonctionnement" section.

## [0.3.5] - 2021-10-18
### Added
- Desktop version for the menu pages.

### Changed
- Various styling adjustments.

### Fixed
- "Fonctionnement" steps numbers.
- Menu hover effect (overflow added to dishes title).


## [0.3.4] - 2021-10-17
### Added
- Improved responsivity
- Font style to menu titles.

### Changed
- Separation of the layout "restaurants" and component "restaurant-cards".

### Fixed
- Menu banner radius.
- Missing appearing animation on 4th child (menu pages).
- Adjust restaurant selection cards size.

## [0.3.3] - 2021-10-17
### Added
- Smooth scroll.
- Hover effect on restaurant selection.
- Hover effect on footer links.

### Fixed
- Adjusting paddings.
- Fixing heart overlapping.
- Same footer on every page.

### Changed
- HTML of the buttons : from "button" to "anchor".


## [0.3.2] - 2021-10-17
### Added
- Loading screen animation
- Appearing menu item animation

### Changed
- Source images from "src" folder to "public" folder.


## [0.3.1] - 2021-10-14
### Added
- Improved menu hover animation.

### Fixed
- Directory redirection issues (back to index and banner images).

## [0.3.0] - 2021-10-14
### Added
- Tablet and desktop versions (work in progress).
- Set footer elements as anchors.
- Update readme.


## [0.2.5] - 2021-10-14
### Added
- Specific image banner on menu pages.
- Titles on menu pages.
- Menu item hover animations on every menu mages.
- Heart animation on every menu page.
- Return link icon on menu pages.


## [0.2.4] - 2021-10-13
### Added
- Menu pages animation (menu "À la française" only).


## [0.2.3] - 2021-10-13
### Added
- Turn hearts into checkbox for click animation.

## [0.2.2] - 2021-10-13
### Added
- Improve styling of the cards.
- Heart shape and hover animation.
- Comments in HTML.

## [0.2.1] - 2021-10-12
### Added
- Styling menu pages.

### Changed
- Optimisation images card.
- Renamed "dist" folder into "public"
- Changed h1 title.
- Changed color variables organisation


## [0.2.0] - 2021-10-10
### Added
- Menu pages
- Link to the menu pages in the index page.

## [0.1.5] - 2021-10-09
### Changed
- refactoring code

### Added
- Variables (colors)
- Mixins (text and background color)

### Fixed
- W3C validator errors.

### Removed
- _logo.scss (replaced by the mixin "background-logo-color")

## [0.1.4] - 2021-10-08
### Added
- styling footer section.
- _footer.scss
- new icons.

## [0.1.3] - 2021-10-08
### Added
- styling restaurants section.
- _restaurants.scss

## [0.1.2] - 2021-10-08
### Added
- styling fonctionnement section.
- _fonctionnement.scss
- _icons.scss

## [0.1.1] - 2021-10-07
### Added
- styling hero section.
- icons folder
- -hero.scss
- _base.scss
- _buttons.scss

## [0.1.0] - 2021-10-06
### Added
- styling header (src/layouts/_header.scss).
- Link to "Shrikhand" font.
- README.
- CHANGELOG.

### Changed
- Version of the project in "package.json" (and package-lock.json) set to match with this changelog.

## [0.0.1] - 2021-10-06
### Added
- Initial commit.
- Setting up file structure.
- "index.html".
- "main.scss" and "_typography.scss".
