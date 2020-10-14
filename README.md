# Getting Started with React.js

### NodeJS

```
sudo npm cache clean -f
sudo npm install -g n
sudo n stable  -> to install latest stable
sudo n latest  -> to install latest
sudo n rm 6.0.0     # replace number with version of Node that was installed to unsinstall
sudo npm uninstall -g n
```

### Create React App

```
npx create-react-app app-name
cd app-name
npm start
```

Note: Make sure you set the JS version of your EDI to React JSX to prevent XML errors

### Hello World

* In the src/ folder go to App.js
* Edit the text between the `<p>` tags in the `<header>`
* Go to http://localhost:3000/ to see the result!