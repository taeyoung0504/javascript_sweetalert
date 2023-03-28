# javascript_sweetalert
자바스크립트 sweetalert 테스트

 

 

SweetAlert2
자바스크립트로 웹 프로그래밍을 하다 보면 자주 Alert 함수를 사용하게 됩니다. Alert는 사용자에게 알림을 주고자 할 때 정말 자구 사용하는 컴포넌트 입니다. 다음과 같이 자바스크립트의 alert는 아주 기본적인 브라우저 UI를 제공하고 있습니다.


<!DOCTYPE html>
<html lang="ko">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>
</title>
</head>
<body>
    <button onclick="alert('기본 alert')">클릭</button>
</body>
</body>
</html>

기본 alert 창
 

해당 기본 alert창을 더 예쁘게 만들고 싶어 해당 방법에 대해 검색해 보았고

SweetAlert2 라이브러리를  알게 되어 사용방법을 블로그에 작성함.


SweetAlert를 사용하여 만든 alert 창
 

 

SweetAlert2 사용방법
SweetAlert2 홈페이지를 접속 : https://sweetalert2.github.io/

 
SweetAlert2

A beautiful, responsive, customizable and accessible (WAI-ARIA) replacement for JavaScript's popup boxes

sweetalert2.github.io
 

해당 홈페이지 하단에 아래 사진과 같이 표시된 부분을 html 소스 코드안에 넣으면  SweetAlert2 라이브러리를 사용가능하다


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
 

다음 아래와 같이 함수(function) 를 이용하여 alert의 속성을 변경하며 디자인을 바꿀 수 있다.

function alert() {

    Swal.fire({
        position: 'center', // alert창 위치 지정
        icon: 'success',
        title: '로그인 성공'        
    })
}

 

공식 홈페이지를 참조하면 더욱 다양한 alert창 변경 디자인 소스를 얻을 수 있다.

 



 

 
