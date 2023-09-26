# Changelog

## [1.5.6] - 2023-09-26

### Notable changes:
- Fix for "[Intervention] Ignored attempt to cancel a touchmove event with cancelable=false, for example because scrolling is in progress and cannot be interrupted." error
- Explicitly set passive: false. Fix for "Violation] Added non-passive event listener to a scroll-blocking <some> event. Consider marking event handler as 'passive' to make the page more responsive" warning.

## [1.5.0] - 2020-01-16

### Notable changes:
- Recreated build tools using Rollup
- Updated all dependencies to its latest versions
- Switched from Travis CI to GitHub Actions
- Added Dependabot to keep our dependencies up-to-date
- Fixed RTL support (#744, #689, #750)
- Fixed `shouldBeConsumedByChild` logic in `mouse-wheel.js` (#841)
- Improved compatibility with parent class (#839)
- Added missing properties in types definition (#808)
- Added support for fractional size of scrolled element (#837)
- Added support for touch devices (#829, #867)
- Added dragging support for mobile devices (#811)
