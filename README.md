# GDG DevFest Pisa 2020 Website 🌎

 [![License](https://img.shields.io/badge/license-MIT%20License-brightgreen.svg)](https://opensource.org/licenses/MIT) [![Twitter](https://img.shields.io/badge/Twitter-@gdgPisa-blue.svg?style=flat)](http://twitter.com/gdgPisa)
 
<p align="center">
  <img src="https://i.imgur.com/wUOVkZk.png" alt="readme screenshot"/>
</p>

:zap: [Live Website](https://devfest.gdgpisa.it/)
🤝 based on [Project Hoverboard](https://github.com/gdg-x/hoverboard)

### Deploying

To contribute to the website, you don't need to clone the repository. The repository is integrated with TravisCI to make sure that the website is re-deployed **whenever there is a new commit**.

The following branches are deployed:

| Branch | Destination | Status |
| ------ | ----------- | ------ |
| `master` | https://devfest-pisa20-debug.firebaseapp.com | [![Build Status](https://travis-ci.com/gdgpisa/hoverboard-2020.svg?branch=master)](https://travis-ci.com/gdgpisa/hoverboard-2020) |
| `release` | https://devfest.gdgpisa.it | [![Build Status](https://travis-ci.com/gdgpisa/hoverboard-2020.svg?branch=release)](https://travis-ci.com/gdgpisa/hoverboard-2020) |

### Setup the project
:book: [Full documentation](/docs/).

Install Node.JS dependencies with:
```
npm install
```

Then start the development server with
```
npm run start
```

This command serves the app at `http://localhost:3000` and provides basic URL routing for the app:

:book: Read more in [setup docs](/docs/tutorials/set-up.md).

### Build Locally

This command performs HTML, CSS, and JS minification on the application
dependencies, and generates a service-worker.js file with code to pre-cache the
dependencies based on the entrypoint and fragments specified in `polymer.json`.
The minified files are output to the `build`.

```
npm run build
```

:book: Read more in [deploy docs](/docs/tutorials/deploy.md).   

### Acknowledgment

Website based on [Project Hoverboard](https://github.com/gdg-x/hoverboard), template brought by [Oleh Zasadnyy](https://plus.google.com/+OlehZasadnyy)
from [GDG Lviv](http://lviv.gdg.org.ua/).

> *Do you :heart: it?* Show your support - please, [star](https://github.com/gdg-x/hoverboard) the project.

### License

Project is published under the [MIT license](https://github.com/gdg-x/hoverboard/blob/master/LICENSE.md).  
