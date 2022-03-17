# UnityCICD

## About The Project
A boilerplate project making use of GameCI to setup a build pipeline for Unity projects within Github actions. 

## Project Status
| Target Platform             | Done | Status |
|-------------------------|------|--------|
| [WebGL](https://github.com/marketplace/actions/unity-builder) | ✔ | [![Actions Status](https://github.com/game-ci/unity-builder/actions/workflows/build-tests.yml/badge.svg?branch=main)](https://github.com/game-ci/unity-builder/actions/workflows/build-tests.yml) |
| [Windows Mono](https://github.com/marketplace/actions/unity-builder) | ✔ | [![Actions Status](https://github.com/game-ci/unity-builder/actions/workflows/build-tests.yml/badge.svg?branch=main)](https://github.com/game-ci/unity-builder/actions/workflows/build-tests.yml) |
| [Linux Mono](https://github.com/marketplace/actions/unity-builder) | ✔ | [![Actions Status](https://github.com/game-ci/unity-builder/actions/workflows/build-tests.yml/badge.svg?branch=main)](https://github.com/game-ci/unity-builder/actions/workflows/build-tests.yml) |

## Getting Started

### Actions
3 Workflow have been setup for the project
1. Acquire activation file - All actions use a Unity installation, which needs to be activated via a license. This only needs to be run once to aquire a license. More information can be found here - https://game.ci/docs/github/activation
2. CI Multi Platform (Simple) - A simple workflow action outputting to multiple platforms, all using the same output parameters. 
3. CI Template with WebGL deploy - A more comprehensive worflow including automated testing, building to Android, Windows and WebGL with expandability for custom parameters, and deploying WebGL to Github Pages.

## Reference
https://game.ci/docs/github/getting-started

## License
[MIT](https://choosealicense.com/licenses/mit/)
