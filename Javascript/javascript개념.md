### javascript를 사용하는 이유?

- HTML 조작과 변경이 목적.
<br>

### 조작 하는 이유는?

- 탭, 모달 등 웹페이지 ui를 만들 수 있다.

- 유저가 입력한 데이터를 검사할 수도 있음
  
- 유저가 버튼을 누르면 서버로 데이터 요청을 할 수도 있음
  
- 서버와 통신이 가능함
  
- 비동기처리 자료 다루기 등 여러 기능을 만들 수 있는게 js!!

---

### 기본 풀이
  
     document : 문서, 여기선 html 웹문서를 뜻함
     
     마침표 : ~의
     
     getElementByid('대상') : 아이디가 '대상'인 html 요소(일명 elemnet)를 찾아라
     
     innerHTML : 내부 HTML 안에서
     
     = : 등호는 프로그래밍에서 오른쪽에 있는걸 대입하라는 뜻
     
    '안녕' : 안녕이라는 문자(큰 따옴표, 작은 따옴표 안에 담겨있으면 항상 문자)


#### ex) 예시
     document.getElementByid('hello').innerHTML = '안녕';

웹문서의 ID='hello'를 찾아서 그거의 내부 html에 '안녕'을 집어넣어라 라는 뜻
<br><br><br>

-     .getElementByid()는 '셀렉터'라고 부름. html요소를 찾기 위해 사용함
-     .innerHTML / .style / .color 이렇게 점 찍는데 괄호없는건 메소드(또는 함수)라고 부름.
-     html 요소의 어떤 속성을 변경할지 결정하기 위해 사용함

### 응용

뒤에 여러개의 메소드를 불러와서 사용할 수 있음

    document.getElementById('???').??? = '???';
-> 여기서 물음표만 마음대로 바꾸면 html의 모든걸 변경하고 조작할 수 있음!

    document.getElementById('test1').src = 'profile.jpg';
이렇게 하면 원하는 요소에 src="profile.jpg"를 추가할 수 있고

    document.getElementById('test1').style.color = 'red';
이렇게 하면 style ="color : red"를 추가할 수 있음

- 매우매우매우 방법이 많기 때문에 필요할때마다 google에서 찾아서 쓰자!

---
