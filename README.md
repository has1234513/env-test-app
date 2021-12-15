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
docker build -t envtest .
```

### run docker container
```
export VUE_APP_VARIABLE_1=sdfgbsdfg
export VUE_APP_VARIABLE_2=asdfghyd
docker run -it -p 8080:80 -e VUE_APP_VARIABLE_1=$VUE_APP_VARIABLE_1 -e VUE_APP_VARIABLE_2=$VUE_APP_VARIABLE_2 --rm envtest
```

### run with docker-compose
```
docker-compose up --build envtest
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
