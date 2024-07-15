## 새로운 문법

```js
// Link로 props로 보내고 싶을때 (params 쓰지 않고)
<Link
  to={`/updateForm/${board.id}`}
  className="btn btn-warning"
  state={{ title: board.title, content: board.content }}
>
  수정
</Link>
```

```js
// 받을때
const location = useLocation();
const { title, content } = location.state;


## 설치 라이브러리

```sh
npm i react-router-dom
```

```sh
npm i styled-components
```

```sh
npm i react-redux
npm install @reduxjs/toolkit react-redux
```

```sh
npm i jwt-decode
```

```sh
npm i react-bootstrap
```

```sh
npm i axios
```

```sh
npm i react-bootstrap-icons
```