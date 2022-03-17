# UnityCICD

## About The Project
A boilerplate project making use of GameCI to setup a build pipeline for Unity projects within Github actions. 

## Project Status
| Target Platform             | Done | Status |
|-------------------------|------|--------|
| [Request activation file](https://github.com/marketplace/actions/unity-request-activation-file) | ✔ | [![Acquire activation file](https://github.com/rosshaydenkelly/UnityCICD/actions/workflows/activation.yml/badge.svg)](https://github.com/rosshaydenkelly/UnityCICD/actions/workflows/activation.yml) |
| [Multi Platform Build](https://github.com/marketplace/actions/unity-builder) | ✔ | [![CI Multi Platform (Simple)](https://github.com/rosshaydenkelly/UnityCICD/actions/workflows/main.yml/badge.svg)](https://github.com/rosshaydenkelly/UnityCICD/actions/workflows/main.yml) |
| [CI template](https://github.com/rosshaydenkelly/UnityCICD/actions/workflows/mainWebDeploy.yml) | ✔ | [![CI Multi Platform (Simple)](https://github.com/rosshaydenkelly/UnityCICD/actions/workflows/main.yml/badge.svg)](https://github.com/rosshaydenkelly/UnityCICD/actions/workflows/main.yml) |
| [Pages Deploy](https://github.com/rosshaydenkelly/UnityCICD/actions/workflows/pages/pages-build-deployment) | ✔ | [![Actions Status](https://github.com/game-ci/unity-builder/actions/workflows/build-tests.yml/badge.svg?branch=main)](https://github.com/game-ci/unity-builder/actions/workflows/build-tests.yml) |


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
