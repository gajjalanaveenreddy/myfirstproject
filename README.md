#  Open Drinks

<a href="https://www.gajjalanaveenreddy.com">
  <img src="https://www.google.com/img/global/badges/netlify-color-accent.svg"/>
</a>

## Submit a drink recipe

Looking to submit a drink recipe? Check out the Contributing Guidelines first!

See: [CONTRIBUTING.md](CONTRIBUTING.md)

- Check existing recipes in [/src/recipes](/src/recipes)
- Fork and make a pull request with your drink recipe
- Once your Pull Request is approved and merged, the latest update will be published to https://opendrinks.io

Also check out [Issues](https://github.com/alfg/opendrinks/issues) for any open bug fixes or feature requests!

## Development

Open Drinks is built with the following technologies:

- [Vue](https://vuejs.org/)
- [BootstrapVue](https://bootstrap-vue.js.org/)
 

If you are familiar or want to give it a shot, feel free to contribute!

### Prerequisites

- Install version 10.16.3 of Node.js on your machine
- There is [nvm](https://github.com/nvm-sh/nvm) support. If you have nvm installed the following commands will install and start using version 10.16.3

```
nvm install
nvm use
```

### Install

```
npm install
npm run serve
```

### Compiles and minifies for production

```
npm run build
```

### Lint

```
npm run lint
```

### Test

```
npm test
```

### Docker

```
docker build -t opendrinks .
docker run -it -p 8080:80 --rm opendrinks
```


