# Panel using CoreUI Vue

CoreUI is meant to be the UX game changer. Pure & transparent code is devoid of redundant components, so the app is light enough to offer ultimate user experience. This means mobile devices also, where the navigation is just as easy and intuitive as on a desktop or laptop. The CoreUI Layout API lets you customize your project for almost any device – be it Mobile, Web or WebApp – CoreUI covers them all!

### Instalation

``` bash
$ npm install
```
### Basic usage

``` bash
# dev server with hot reload at http://localhost:3000
$ npm run serve
```

Navigate to [http://localhost:3000](http://localhost:3000). The app will automatically reload if you change any of the source files.

#### Build

Run `build` to build the project. The build artifacts will be stored in the `build/` directory.

```bash
# build for production with minification
$ npm run build
```

## Folder Structure

```
├── public/          # static files
│   └── index.html   # html template
│
├── src/             # project root
│   ├── assets/      # images, icons, etc.
│   ├── components/  # common components - header, footer, sidebar, etc.
│   ├── layouts/     # layout containers
│   ├── scss/        # scss styles
│   ├── router       # routes config
│   └── store        # template state example 
│   ├── views/       # application views
│   ├── _nav.js      # sidebar navigation config
│   ├── App.vue
│   ├── ...
│   └── main.js
│
└── package.json
```

## Documentation

The documentation for the CoreUI Admin Template is hosted at our website [CoreUI for Vue](https://coreui.io/vue/)

