# Bulma builder with class namespace #

A simple NPM builder for [bulma.css](https://bulma.io/) with a custom class namespace.

Default class namespace: `bu-`

------

Configure your preferred class namespace in **postcss.config.js**.

#### Initialize

```
npm install
```

#### Build default Bulma with all elements, components, etc.

```
npm run build-all
```

#### Build custom Bulma

Update **bulma-custom.sass** to include only the components you need.

```
npm run build-custom
```

#### Build both default and custom Bulma

```
npm run build
```