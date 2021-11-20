<h1 align="center">VueJS portfolio template</h1>

> Portfolio template using VueJs framework, CosmicJS API and Bootstrap

<p align="center"><strong> Live demo with my personnal data <a href="https://www.adityasingh.xyz/">here</a> ! </strong></p>

<img align="center" src="doc/demo.gif" alt="portfolio-vuejs preview"></img>

---

## Table of Contents

- [Features](#features)
- [Setup](#project-setup)
- [Edit Content](#how-to-edit-content)
- [Author](#author)
- [Contributing](#-contributing)
- [License](#-license)

---

## Features

- Builded with VueJs framework ✨
- One page layout ✨
- Material design ✨
- Bootstrap 4.5 & SCSS ✨
- Responsive ✨
- Animated layout ✨
- Content managed with CosmicJS API ✨

## Project setup

```
npm install
```

### Compiles and hot-reloads for development

```
npm run serve
```

### Compiles and minifies for production

```
npm run build
```

### Lints and fixes files

```
npm run lint
```

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).

## How to edit content

This template have a CMS support with CosmicJS. You can easily put your content there by creating and linking your CosmicJS account.

In order to customize your portfolio, you must create a CosmicJS account and a new fresh bucket on it. Once done, you must update credentials of the **.env** file.

To do this, you just have to modify the variables contained in the ENV file (API token, bucket slug and read key).

```env
# CosmicJS
VUE_APP_COSMICJS_TOKEN=" "
VUE_APP_COSMICJS_BUCKET_SLUG=" "
VUE_APP_COSMICJS_BUCKET_READ_KEY=" "
```

After that, you need to create the object type and data we will use. To do that properly and easily, you can import the json file, located [inside the data folder of this repo](https://github.com/aditya-singh9/portfolio/blob/main/data/bucket.json), by accessing import/export settings inside your bucket settings page.

Now, you can customize it with your data through CosmicJS interface!

## Author

👤 **Aditya Singh**

- Github: [@aditya-singh9](https://github.com/aditya-singh9)
- LinkedIn: [@Aditya Singh](https://www.linkedin.com/in/aditya-singh9/)
- Portfolio: [adityasingh.xyz](https://adityasingh.xyz)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/aditya-singh9/portfolio/issues).

## Show your support

Give a ⭐️ if this project helped you!

## 📝 License

This project is under [MIT](https://github.com/aditya-singh9/portfolio/blob/main/LICENSE) license.
