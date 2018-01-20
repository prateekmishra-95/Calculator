
# Calculator
Calculator React App that implements the concept of React with Redux. 

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You’ll need to have Node >= 6 on your machine and a modern web browser. 

### Installing

First install [Node](https://nodejs.org/en/download/).
After installation check the version of ```npm``` (run the following command in the terminal):
```
npm -v
```
If you have ```npm``` 5.2.0+ installed, you may use npx:
```
npx create-react-app Calculator

cd Calculator
```
else run the command : 
```
npm install -g create-react-app

create-react-app Calculator

cd Calculator
```
Create React App is the best way to start building a new React single page application. It sets up your development environment so that you can use the latest JavaScript features, provides a nice developer experience, and optimizes your app for production. Create React App doesn’t handle backend logic or databases; it just creates a frontend build pipeline, so you can use it with any backend you want. It uses build tools like Babel and webpack under the hood, but works with zero configuration.

Now install two more packages ```react-redux``` and ```redux```:
```
npm install react-redux

npm install redux
```
After installation change the ```src``` folder of the ```Calculator``` app just created with the ```src``` folder of this repository that you have cloned on your personal machine.

That's all run the following command and enjoy! 
```
npm start
```

### Folder Structure

After creation, your project should look like this:

```
Calculator/
  README.md
  LICENSE
  package.json
  CONTRIBUTING.md
  public/
    index.html
    favicon.ico
    manifest.json
  src/
    actionCreators/
      actionCreator.js
    actions/
      actions.js
    components/
      CalculatorApp.js
      FinalResult.js
      KeyPad.js
    containers/
      CalculatorContainer.js
    css/
      index.css
    reducers/
      reducer.js
    validations/ 
      validator.js
    index.js    
```

For the project to build, **these files must exist with exact filenames**:

* `public/index.html` is the page template;
* `src/index.js` is the JavaScript entry point.

You can delete or rename the other files.

You may create subdirectories inside `src`. For faster rebuilds, only files inside `src` are processed by Webpack.

Only files inside `public` can be used from `public/index.html`.

You can, however, create more top-level directories.

## Built With

* [ReactJS](https://reactjs.org/) - The web framework used
* [Redux](https://redux.js.org/) - For state management
* [ECMASCRIPT 6](http://es6-features.org/#Constants) - Standard used to write Javascript code
* [Babel](https://babeljs.io/) - Transpiler used

## Contributing

Please read [CONTRIBUTING.md](https://github.com/prateekmishra-95/Calculator/blob/master/CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Authors

* **Prateek Mishra** - [prateekmishra-95](https://github.com/prateekmishra-95)

## License

This project is licensed under the Apache License - see the [LICENSE.md](https://github.com/prateekmishra-95/Calculator/blob/master/LICENSE) file for details
