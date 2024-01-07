### Add dependencies to the sub module

```bash
# add one
yarn lerna add <library> --scope=@lerna-ts/<module_name>
yarn lerna add ts-mixer --scope=@lerna-ts/version-timeline
yarn lerna add @lerna-ts/reunion --scope=@lerna-ts/comparator

# add all
yarn lerna add @types/jest

# add all dev 
yarn lerna add @types/jest --dev

# upgrade
yarn lerna exec -- yarn add typescript@latest
yarn lerna exec -- yarn add @types/jest@latest

# @types/node
```

### Document Ref
- add library to specific module
  - https://futurestud.io/tutorials/lerna-install-dependencies-for-a-specific-package
  - https://www.npmjs.com/package/@lerna/add