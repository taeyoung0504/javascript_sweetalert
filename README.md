
# sweetalert2
자바스크립트로 웹 프로그래밍을 하다 보면 자주 Alert 함수를 사용하게 됩니다.

Alert는 사용자에게 알림을 주고자 할 때 정말 자구 사용하는 컴포넌트 입니다. 

다음과 같이 자바스크립트의 alert는 아주 기본적인 브라우저 UI를 제공하고 있습니다.


## SweetAlert2 사용방법
# SweetAlert2 홈페이지를 접속 : https://sweetalert2.github.io

홈페이지 하단의 소스코드를 html 안에 넣으면 SweetAlert2 라이브러리를 사용가능하다

```HTML
<!DOCTYPE html>
<html lang="ko">
<head>
<link href="https://cdn.jsdelivr.net/npm/@sweetalert2/theme-dark@4/dark.css" rel="stylesheet">
<script src="https://cdn.jsdelivr.net/npm/sweetalert2@11/dist/sweetalert2.min.js"></script>
<script src='sweetalert.js'></script>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>
</title>
</head>
<body>
    <button onclick="alert()">클릭</button>
</body>
</body>
</html>
```

그후 다음 아래와 같이 함수(function) 를 이용하여 alert의 속성을 변경하며 디자인을 바꿀 수 있다.
```
function alert() {

    Swal.fire({
        position: 'center', // alert창 위치 지정
        icon: 'success',
        title: '로그인 성공'        
    })
}
````

<img src="https://user-images.githubusercontent.com/128016593/228177928-7c5f005d-d5ae-4072-b3d1-3f3ed6248623.png" width="1000">


