# Webpack 3 Boilerplate for beginners
A basic webpack 3 boilerplate for beginners to start with any JS/ES6 based project. Webpack 4 has been released, but we are continuing with webpack 3 until all necessary plugins work together without issue.
<br>
## Guide
This basic boilerplate is the final output of this comprehensive write up on Medium. I recommend to read this article to know the insight of how you can configure webpack from scratch.
[Webpack 3 quickstarter: Configure webpack from scratch](https://medium.com/@nirjhor123/webpack-3-quickstarter-configure-webpack-from-scratch-30a6c394038a)
<br>
1. Navigate to your "class projects" folder (where we will be placing exercises). NOTE: Start from your home directory "~".

```
$ cd "desktop/class projects"
```

2. Clone the webpack-starter into your "class projects" folder with the following command:

```
$ git clone https://github.com/SJCCodeTalk/webpack-starter.git
```

3. Change your directory to the project folder. 

```
$ cd webpack-starter
```

4. Install dependencies

```
$ npm install
```


5.  Develop locally with webpack-dev-server

```
$ npm run dev
```

## Bundled Output
In your browser, navigate to: [http://localhost:2000/](http://localhost:2000/)

### For bundled output

```
$ npm run build
```

## For production-ready output

```
$ npm run build:prod
```
 
## Loaders and Plugins used in this boilerplate

### Loaders
* babel-loader
* html-loader
* sass-loader
* css-loader
* style-loader
* file-loader

### Plugins
* clean-webpack-plugin
* extract-text-webpack-plugin
* html-webpack-plugin

# mealworx
