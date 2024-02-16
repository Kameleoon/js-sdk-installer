# Kameleoon SDK Installer

## Introduction

Kameleoon SDK Installer is the small binary helper tool for Kameleoon SDK installation.

For more information on SDKs refer to [Official Kameleoon Documentation](https://developers.kameleoon.com/feature-management-and-experimentation/overview)

## Installation

- Install the package globally:

  - **npm** - `npm install --global @kameleoon/sdk-installer`
  - **yarn** - `yarn global add @kameleoon/sdk-installer`
  - **pnpm** - `pnpm add -g @kameleoon/sdk-installer`
  - **bun** - `bun install --global @kameleoon/sdk-installer`

- Then run:

```
$ kameleoon-sdk
```

- Alternatively use `npx` to run `kameleoon-sdk` script without installing:

```
$ npx @kameleoon/sdk-installer
```

## How to Use

After running the command several questions will be asked to configure you SDK setup.

The script won't install any dependencies on it's own, but will generate an installation command depending on your package manager and the prompt replies.

It's highly recommended to generate provided code example to avoid confusion when working with SDK setup for the first time.
