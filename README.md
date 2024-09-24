# Introduction
This repository facilitates both the Administrator guide, and the User guide.
The documentation can be rendered with either Docusaurus or mkdocs.

# Setup
## Docusaurus
1. Install node (e.g `brew install node`)
2. `npm install`
3. `npm run build`
4. `npm start` 
## Mkdocs
1. Install mkdocs (pip install mkdocs)
2. mkdocs server



# Website

This website is built using [Docusaurus](https://docusaurus.io/), a modern static website generator.

### Installation

```
$ yarn
```

### Local Development

```
$ yarn start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Build

```
$ yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Deployment

Using SSH:

```
$ USE_SSH=true yarn deploy
```

Not using SSH:

```
$ GIT_USER=<Your GitHub username> yarn deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.