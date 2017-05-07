# pstestjs4nodemocha_nt
## 2. Testing Your JavaScript
### 3 Node Versions
```
nvm use --lts
```

## 3. Testing with Mocha
### 5 Testing Something Real
```
mocha "./test/**/*.spec.js"
```
add to npm script
```
"test": "mocha ./test/**/*.spec.js"
```


## 4. BDD Style Assertions
### 6 Dealing with Nulls
```
var N = null;
should.not.exist(N);
```

### 7 Working with Promises
```
npm install --save chai-as-promised
```
