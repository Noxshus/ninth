# ninth

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


-------------------

Built following this guide: https://learnvue.co/articles/deploy-vue-to-github-pages

First time only step, set origin: git remote add origin https://github.com/your username/github project name.git

npm run build
git add dist && git commit -m 'adding dist subtree'
git subtree push --prefix dist origin gh-pages
