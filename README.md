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

code
```
function f(role,cb){
  return new Promise(function(resolve){
    setTimeout(function(resolve(roles.indexOf()}=0)},0);
  }
}
```
test
```
return controller.isPromise('admin').should.eventually.be.true;
```

beginning:
```
var cap = require("chai-as-promised");
chai.use(cap);
```

## 5. Spys, Stubs, and Mocks
### 3 Working with Spys
```
function getIndex(req,res){
  res.render('index');
}
```

test
```
it('should',function(){
  var req={};
  var res={
    render:sinon.spy()
  };
  authController.getIndex(req,res);
  res.render.calledOnce.should.be.true;
  res.render.firstCall.args[0].should.equal('index');
})
```

### 4 Watching Existing Functions
```
beforeEach(function(){
  user={
    roles:['user'],
    isAuthorized:function(neededRole){
    }
    sinon.spy(user,"isAuthorized");
    authController.setUser(user);
  }
})
```

## 6. Testing Real Things
```

```
