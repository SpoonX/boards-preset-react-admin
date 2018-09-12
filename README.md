# boards-preset-react-admin

[Admin on rest](https://marmelab.com/react-admin) preset for the [Boards CLI](https://github.com/SpoonX/boards-cli).

## Installing

`yarn global add boards-preset-react-admin` or `npm i -g boards-preset-react-admin`

## Quick start

To see this boards preset in action and create a fully functional dashboard in under 5 minutes, follow these steps:

1. `yarn global add boards-cli boards-preset-react-admin`
2. `boards ra:init my-project`
3. `cd my-project`
4. `boards ra:resource posts`
5. `boards ra:resource albums`
6. `yarn start`
7. Pick up your jaw, and get productive.

## Tasks

This preset adds the following tasks to your project.

### ra:init

Initializes a new Admin on Rest project.

`boards ra:init my-project`

### ra:resource

Create a full resource with edit, create, list and delete enabled. Also attaches resource to App.js.

`boards ra:resource resourceName`

### ra:list

Creates a new resource with only listing (readonly resource).

`boards ra:list resourceName`

### ra:edit

Adds edit to an existing resource that previously didn't have edit enabled.

`boards ra:edit resourceName`

### ra:create

Adds create to an existing resource that previously didn't have create enabled.

`boards ra:create resourceName`

## License

MIT