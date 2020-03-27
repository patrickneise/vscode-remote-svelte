# VS Code Remote Development Container: Svelte

This is a **[VS Code Remote - Container](https://aka.ms/vscode-remote/containers)** for **[Svelte](https://svelte.dev/)** web app development.

## Setting up the development container

Follow these steps to open this sample in a container:

1. If this is your first time using a development container, please follow the [getting started steps](https://aka.ms/vscode-remote/containers/getting-started).

2. To start development with this container:

   - Clone this repository to your local filesystem.

      >NOTE: Replace 'my-project' below with the name of your project

      ```shell
      git clone https://github.com/patrickneise/vscode-remote-svelte.git my-project
      ```
   - [Update the remote URL](https://help.github.com/en/github/using-git/changing-a-remotes-url) for the cloned repo to your projects repository.
   - Press <kbd>F1</kbd> and select the **Remote-Containers: Open Folder in Container...** command.
   - Select the cloned copy of this folder, wait for the container to start, and start developing!

## Development in the container

The container has the following installed:
   - [Svelte](https://svelte.dev/) with the [Svelte project template](https://github.com/sveltejs/template) as a starter.
   - VSCode Extensions installed in the container
     - [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
     - [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
     - [Svelte](https://marketplace.visualstudio.com/items?itemName=JamesBirtles.svelte-vscode)
   - Exposed ports
     - `5000` for development server
     - `35729` for hot reload


Start the development server:
```shell
yarn dev
```