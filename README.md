# FOSJsRoutingBundle

This package automatically tracks the latest release of
[FriendsOfSymfony/FOSJsRoutingBundle](https://github.com/FriendsOfSymfony/FOSJsRoutingBundle)
and publishes the updated **router.min.js** to NPM without any dependencies.

Unlike the base project, your `package.json` will no longer depend on composer,
and you will be able to install your dependencies independently.

## What it does

- Fetches `router.min.js` from the latest upstream tag.
- Updates the package version to match the upstream release.
- Publishes the updated file to NPM.

## Installation

Use the version that the one installed using composer:
```bash
npm install "@crovitche/fos-js-routing-bundle@3.5.2"
```

## Usage
```bash
import Routing from "@crovitche/fos-js-routing-bundle/router.min";
```

From here, you can refer to the official documentation:
https://github.com/FriendsOfSymfony/FOSJsRoutingBundle/blob/master/Resources/doc/usage.rst


