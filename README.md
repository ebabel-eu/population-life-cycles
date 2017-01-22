# UPDATE

This repository has moved to Bitbucket and is no longer updated.

The production version of this game is available on https://magicalhex.com/

# population-life-cycles
Population life cycles simulates adding a group of individuals that will reproduce, grow old and die.

## Install

```
npm install
```

## Build only once for Production

```
npm run build
```

## Run locally

```
npm start
```

Browse to http://localhost:8080 or whichever port is available.

## Develop and build continuously for Development

```
npm run dev
```

## Unit testing

```
npm test
```

Browse to ./coverage/lcov-report/index.html for the report.

## Lint both Sass and Javascript

```
npm run lint
```

Browse to ./linters/ for the html reports.

## Lint the Sass

Note: when there is nothing to report, the output doesn't produce a file.

```
npm run lint_scss
```

Browse to ./linters/scss-report.html to view the Sass linting report.

## Lint the Javascript

```
npm run lint_js
```

Browse to ./linters/js-report.html to view the Javascript linting report.

## Deploy to production

Publish any changes to the gh-pages branch and browse to https://ebabel-eu.github.io/population-life-cycles/

## Tasks

See https://github.com/ebabel-eu/population-life-cycles/issues

## Release planning

See https://github.com/ebabel-eu/population-life-cycles/milestones

## Version history

- 1.3.0: Mobs don't collide (one mob per hexagon).
- 1.2.0: Mobs move around.
- 1.1.0: Canvas world to see where mobs are.
- 1.0.0: Basic version with mobs but without canvas world.

See https://github.com/ebabel-eu/population-life-cycles/releases

### Tag a new version for a release

Before releasing, make sure to build for Production:

```
npm run build
```

Note: only do this from the master branch after all code is ready to be published.

```
git tag -a 1.3.0 -m "Mobs don't collide (one mob per hexagon)."
```

To write multiple lines:

```
git tag -a 1.4.0 -m "First line
second line
last line"
```
