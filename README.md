# Local
## Test
```bash
npm test
npm install mocha --save-dev


```

# Container
## Test
```bash
docker build --no-cache --target test .
```
## Build
```bash
docker build --target base -t node-webapp-test .
```

## Run the container
```bash
docker run -dp3000:3000 node-webapp-test
```
