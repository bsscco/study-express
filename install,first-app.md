# install

```cli
mkdir myapp
cd myapp
npm init
npm install express-generator -g
express -h #도움말
express -v jade #이후 y입력
```

# first-app
app.js 하단에 추가
```javascript
app.listen(3000, function () {
  console.log('Example app listening on port 3000!');
});
```
```cli
cd myapp
node app.js
```
