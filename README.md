# Module Development Environment Template with Typescript

Template for NodeJS module development with Typescript inside a VSCode Docker Container.

## Requirements

- [Docker Engine](https://docs.docker.com/engine/install/)
- [Docker Compose](https://docs.docker.com/compose/install/)

- [Visual Studio Code](https://code.visualstudio.com/)
- [VS Code Remote Development Extension](https://aka.ms/vscode-remote/download/extension)
- [VS Code Docker Extension](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker) *(optional)*

## Usage

1. Click **Use this template**
1. Select **Create a new repository**
1. Check the .devcontainer/docker-compose.yml file to disable unwanted services.
1. Create the .devcontainer/.env file from .env-defaults (update the HOST_PREFIX value!).
1. Update the package.json file. Set the package name and description.
1. Run the **Remote-Containers: Reopen in Container...** command from the Command Palette (F1) or quick actions Status bar item.
1. Install the dependencies.

### To return to the local project:
- Run the **Remote-Containers: Reopen Locally...** command from the Command Palette (F1) or quick actions Status bar item.

## Development Container

The container includes NodeJS (check .env to change version), with pnpn and Yarn installed globally.

### Project Development Libraries

- [Typescript](https://www.typescriptlang.org/)
- [Typedoc](https://typedoc.org/) for generating documentation from the ts source files.
- [Jest](https://jestjs.io/) with [ts-jest](https://kulshekhar.github.io/ts-jest/) for testing.
- [ESLint](https://eslint.org/) for static code analysis.

## Docker Services Included

- MSSQL
- Postgres (with pgAdmin)
- MySQL (with phpMyAdmin)
- MariaDB (with phpMyAdmin)
