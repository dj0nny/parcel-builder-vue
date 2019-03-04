# parcel-bundler-vue

> Set up a Vue.js web app using Parcel

__[Parcel](https://parceljs.org/)__ is bundler for web application. This repo is an example of using Parcel to configure an app that uses the __Vue.js__ framework.

## Getting Started

### Prerequisites

You must have __Npm__ or __Yarn__ installed on your machine

### Installing

Clone the repository using __Git__:
`https://github.com/dj0nny/parcel-bundler-vue.git`

Or __download__ the repo [here](https://github.com/dj0nny/parcel-bundler-vue/archive/dev.zip)

### Running the application

Type `npm install` or `yarn install` for installing the dependencies. At the end type `npm run dev` or `yarn run dev` for creating a `/dist` folder with all bundled files and running the Parcel server for the project.

### Create a production version

Run `npm run prod` or `yarn run prod` for creating an optimized production version of this project

## Create a new Parcel project

Inside a folder, open a terminal and type `npm init -y` or `yarn init -y` for creating a new `package.json` file. If you want a custom configuration, remove the `-y` flag from the command. Now, into the `package.json` file, in the `scripts` section, add:
```json
  "scripts": {
    "dev": "parcel src/index.html",
    "prod": "parcel build src/index.html"
  }
```

The `index.html` file is the entry point where the app will be render, if you'll use a framework like React or Vue for example.

### Install Parcel

Into the terminal run `npm install -D parcel-bundler` or `yarn add parcel-bundler --dev` for installing Parcel as a dev dependency.

### Add you files

Now you can add your project's files into the folder. I'll suggest you to create a subfolder called `src` and work inside it.
Also create a `index.js` file for adding custom packges or code.

For more info see the [official documentation](https://parceljs.org/)

## Built with ❤ using:

* [Parcel](https://vuejs.org/) - A bundler for web application
* [Vue.js](https://vuejs.org/) - A Javascript framework


## Contributing

Of course Pull Requests ⇄ for imporving this project and ★ are welcome.