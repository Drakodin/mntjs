# mnt.js
Client-side programmatic file loading library for static webpages

## Overview
Folder paths in public always render as page consisting of files and act like a virtual file system in HTML. This library hijacks that functionality to extract those files from the HTML page, with customizability in the form of option arguments.

## Usage
### Requirements
- Node.js
  - All Node applications have a "server" underneath that is HTTP/S enabled.
  - Vanilla JS will run into CORS with HTTP requests

### Recommended Development
- TS >= 4.x
- App deployment with a "public" directory for static assets
  - This library assumes a public path exists from which the application is deployed
  - It does not need to be named "public". It just has to be where the contents of the page reside

### Installation
#### (If available) NPM/Yarn
This project will become a Node module for ease of access in Node projects. If it is not published into NPM, then install using the Github link.

To install, copy the following command, depending on your package manager. Adding it to `"devDependencies"` is optional.
```
# If NPM
npm i @drakodin/mntjs

# If Yarn
yarn add @drakodin/mntjs
```

#### Downloading source code
Releases will have their own branch. Installation using package managers can be done from these branches into modules. Otherwise, all versions will be tagged with their source archives under each. This can be found in "Releases" on the repository's page.
