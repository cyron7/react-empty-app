# The PRoject
This is to better understand ReactJS and be better at using it
## The bare minimum of what you need to create a react app
- **index.html file:** This is what we will send to the client and what our react app will render into
- **Support for ES6:** Want to be able to write in modern JS syntax
- **Webpack:** Takes care of building our app and loading of CSS modules. Will also use to server our app during development
- **Root component:** This is the base of our component tree. It is the container that holds the application
- **react-hot-loader:** Allows us to see the changes in our app immediatly without having to do refresh

## Important Commands
### Installing babel 
```
npm install --save-dev @babel/core @babel/cli @babel/preset-env @babel/preset-react
```
### Installing Webpack 
```
npm install --save-dev webpack webpack-cli webpack-dev-server style-loader css-loader babel-loader
```
### Running web pack server
```
npx webpack-dev-server --mode development
```