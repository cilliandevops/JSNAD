## commands

### Help commands

```javascript
node --help
```

### Checking Syntax

```javascript
node --check app.js

node -c app.js
```

### Node can directly evaluate code from the shell.

```javascript
node --print "1+1"
```

### Preloading CommonJS Modules

```javascript
node -r ./preload.js app.js
```

### Stack Trace Limit

```js
node --stack-trace-limit=101 app.js 
```