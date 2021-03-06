# `Pocket Trailer` — Projecto final da formação de AngularJS feita na Citeforma

Este projecto foi desenvolvido durante as aulas da formação de AngularJS, realizada na Citeforma.
Utilizou-se Angular na sua versão 1.

A base do projecto acenta na base definida no projecto angular-seed disponivel no GitHub.


## Getting Started

To get you started you can simply clone the `AngularJS` repository and install the dependencies:

### Prerequisites

You need git to clone the `AngularJS` repository.
You must have Node.js and its package manager (npm) installed.

### Clone `AngularJS`

Clone the `AngularJS` repository to the desired destination folder, using git:

```
git clone https://PedroEFLourenco@bitbucket.org/PedroEFLourenco/angularjs.git
```

If you just want to start a new project without the `AngularJS` commit history then you can do:

```
git clone --depth=1 https://PedroEFLourenco@bitbucket.org/PedroEFLourenco/angularjs.git <your-project-name>
```

The `depth=1` tells git to only pull down one commit worth of historical data.

### Install Dependencies

We have two kinds of dependencies in this project: tools and Angular framework code. The tools help
us manage and test the application.

* We get the tools we depend upon via `npm`, the [Node package manager][npm].
* We get the Angular code via `bower`, a [client-side code package manager][bower].
* In order to run the end-to-end tests, you will also need to have the
  [Java Development Kit (JDK)][jdk] installed on your machine. Check out the section on
  [end-to-end testing](#e2e-testing) for more info.

We have preconfigured `npm` to automatically run `bower` so we can simply do, from the "app" folder:

```
npm install
```

Behind the scenes this will also call `bower install`. After that, you should find out that you have
two new folders in your project.

* `node_modules` - contains the npm packages for the tools we need
* `app/bower_components` - contains the Angular framework files

*Note that the `bower_components` folder would normally be installed in the root folder but
`angular-seed` changes this location through the `.bowerrc` file. Putting it in the `app` folder
makes it easier to serve the files by a web server.*

### Run the Application

We have preconfigured the project with a simple development web server. The simplest way to start
this server is:

```
npm start
```

Now browse to the app at [`localhost:8000/index.html`][local-app-url].


## Contact

For more information on AngularJS please check out [angularjs.org][angularjs].


[angularjs]: https://angularjs.org/
[bower]: http://bower.io/
[git]: https://git-scm.com/
[http-server]: https://github.com/indexzero/http-server
[jasmine]: https://jasmine.github.io/
[jdk]: https://wikipedia.org/wiki/Java_Development_Kit
[jdk-download]: http://www.oracle.com/technetwork/java/javase/downloads
[karma]: https://karma-runner.github.io/
[local-app-url]: http://localhost:8000/index.html
[node]: https://nodejs.org/
[npm]: https://www.npmjs.org/
[protractor]: http://www.protractortest.org/
[selenium]: http://docs.seleniumhq.org/
[travis]: https://travis-ci.org/
[travis-docs]: https://docs.travis-ci.com/user/getting-started
