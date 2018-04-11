# What?

Docker image with cypress installed in it, so you don't have to do `npm install cypress` yourself.

# How to Use?

Given you are in the root directory of your application (where your `cypress/` folder lives), run your tests with:

```
docker run -w=/app/ -v $(pwd):/app dudadornelles/cypress  /node_modules/.bin/cypress run
```
