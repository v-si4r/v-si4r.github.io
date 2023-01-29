# About

This is Vadym's Sichkar personal website. 
The theme takes visual inspiration from [Ataraxia](https://gersonbdev.github.io/) by [Zola](https://www.getzola.org/).

## Pre-requisites

- [Node.js](https://nodejs.org/)
- [Sass compiler](https://sass-lang.com/install)
- [Zola cli](https://www.getzola.org/documentation/getting-started/installation/)

## Hacking

By default, the theme comes with all the scss styles already compiled, in such a way that the installation of Bootstrap is not necessary, in order to avoid dependencies such as Node.js in the production file.

```bash
npm install
```

```bash
sass --watch scss/custom.scss:static/assets/css/custom.css
```

## Hosting

In the root run the following command:
```
zola serve
```

## Configuration

To change the configuration, edit the `config.toml` file. 

> To find a detailed description of the following configuration variables go to https://www.getzola.org/documentation/getting-started/configuration/

All static content:
- `static\images` - all image resources
- `static\assets` - pages and more

Basic templates are located in the `templates` directory