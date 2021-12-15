# env-test-app

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

### build docker container
```
docker build -t vuejs-runtime-environment-variables .
```

### run docker container
```
docker run -it -p 8080:80 --env-file=.env.staging.local --rm vuejs-runtime-environment-variables
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
