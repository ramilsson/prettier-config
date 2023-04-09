# @ramilsson/prettier-config

## Installation

- Create `.npmrc` file in the root directory and include this lines:

  ```
  @ramilsson:registry=https://npm.pkg.github.com
  //npm.pkg.github.com/:_authToken=${YOUR_PERSONAL_ACCESS_TOKEN}
  ```

- Install the package:
  ```
  npm install @ramilsson/prettier-config --save-dev
  ```

## Usage

- Reference the package in `package.json`:

  ```
  {
    "name": "my-cool-library",
    "version": "0.1.0",
    "prettier": "@ramilsson/prettier-config"
  }
  ```
