# [참고](http://expressjs.com/ko/starter/basic-routing.html)

### 라우트 코드
```javascript
// 형식
app.METHOD(PATH, HANDLER)

// 예시
app.get('/', function (req, res) {
  res.send('Hello World!');
});
```
