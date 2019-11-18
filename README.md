# Frontend Monorepo

### Overview

This is a monorepo architecture for our Frontend products. The idea behind this
repository is to enhance the experience when working with different packages and cross dependencies.

### Using the repository

At the moment, all the different packages live under `packages` directory.

After cloning the repository, you should run:

```bash
$ yarn install
```

This will bootstrap all the packages for you.

### Registering cross dependencies

In order to make `package-b` depend on `package-a` you should run:

```bash
$ lerna add @up42/<package-a> --scope @up42/<package-b>
```

Which reads like: "Add dependency `package-a` into scope `package-b`"

#### Packages

- `packages/constellation-tokens`: `@up42/constellation-tokens`
