# HTML 기능

### html의 주석 : 컨+물음표

-     HTML : Markup Language
- 자료가 어디에 어떻게 배치되어있나 표현하기 위한 언어
<br>

### 이미지 넣기
![Untitled 1](https://github.com/kimhaaneul/study/assets/158141404/74ba5099-94b5-47b2-864f-35695a300d0b)

-     img src=”./폴더/파일명.확장자”

→src는 ‘속성’이라고 부름

    - 링크 걸기
    - a href=”주소 입력”
### 버튼 만들기
![Untitled 3](https://github.com/kimhaaneul/study/assets/158141404/99a6df0f-8c4c-411b-8586-a284a58f29ab)
<button>보일 이름</button>

### 리스트 만들기
![Untitled 4](https://github.com/kimhaaneul/study/assets/158141404/c99c4709-48dc-460c-a4ea-1b302f9f89d1)
- 클래스 2개 이상 가능. 2개 이상 클래스 넣을 시

- ul : 리스트를 담아주는 하나의 주머니

- li 원하는 항목1

계속 추가 하면 늘어남!

</ul>

- span 태그
    - 그냥 별 의미없는 태그. 따로 p태그나 안에서 나눌때 쓰면 좋음. 따로 글자색 지정하거나 그럴때…~
    - sapn태그는 해당 태그만 style을 줄 수도 있음! 

---

### Style

- style 속성을 사용하면 모든 스타일 형식을 다 넣을수 있음


 -     style= ”width(가로폭) : 원하는값px;”
 -     style= ”margin-right(오른쪽 여백):원하는값px”
 -     style= ”margin-left(왼쪽 여백): 원하는 값px”
 -     style= ”margin-top(위쪽 여백): 원하는 값px”
 -     style= ”margin-batton(아래 여백):원하는 값px”
 -     style= ”margin(전체여백):원하는 값px”
-      style= ”border(선):원하는 굵기 px sollid black(원하는색상;”
-      style= ”padding(안쪽여백): 원하는 안쪽여백px”
-      style= ”border-radius(라운딩):원하는 값px”

---

### 폰트 스타일
-     style=”font-size:원하는 폰트사이즈px”
-     px: 픽셀 단위
-     vw : 현재 브라우저의 너비에 @로 지정해주세요.
-     %: %단위는 부모 사이즈에 비례
-     ”font-family(글꼴):’설치된 글꼴 영문으로 적기’”
-     ”color:red(영문)”
-     ”letter-spacing(자간간격): 원하는픽셀(+,-)px”
-     <strong> : 글씨 굵게

---

### <div>태그

- div 태그 : 네모난 박스라고 생각하면 된다.

- display : block; —> 박스를 가운데로 정렬해 주는 기능.
    - 기본으로 display기능을 가지고 있음.
    - 하지만 div는 기본으로 block 기능을 가지고 있어서 굳이 안 걸어도 됨.

- display : block 뜻 —> 가로행을 전부 차지해주세요 라는 뜻

→ display 속성에 여러가지 들어있으니 보고 원하는거 쓰면 된다!
<br>
- 박스 안에 들어가면 자동으로 div의 css가 1순위가 된다.
- 자잘한 것들은 div class안에 원하는 style 값들을 넣어두는게 훨씬 깔끔하고 단순하게 할 수 있음.
- div 태그로도 테이블을 만들 수 있음
    -     div style=”display: table” 을 해주면 테이블 처럼 생김
    -     style= “display : table-row” : tr 태그랑 똑같은 기능
    -     style =” display : table-cell” : td랑 똑같은 태그

---

### 박스에 그림자 넣기

- box-shadow: 5px(가로) 5px(세로) 5px(번짐) -5px(그림자크기+,- 다 가능) #fff(색상);

![Untitled 5](https://github.com/kimhaaneul/study/assets/158141404/fb315e24-599e-4729-8ece-50125ef32956)


이렇게 원하는 값으로 넣어주면 된다

![Untitled 6](https://github.com/kimhaaneul/study/assets/158141404/0aa72b93-097c-4278-b837-6c95a953171a)


적용된 모습!!

---

### nav바

- nav :  div 와 똑같음, 하지만 div보다 읽기 쉬울 수 있음
- section : div와 똑같음 = 웹페이지에서 큰 덩어리를 표현하고 싶을 떄 사용
- footer : div와 똑같음 = 웹페이지에서 큰 덩어리를 표현하고 싶을 떄 사용

---

### a태그

-     text-decoration : none; ( 이렇게 설정해주면 태그 아래 밑줄이 사라짐 )  
-     a:link 방문 전 링크  
-     a:visited 방문했던 링크    
-     a:hover 커서가 링크위에 있을 때  
-     a:active 클릭시
    
    ---
    
    ### selector문법
    
-     >: ~(부모)안에 있는 직계 자식
-     (공백): ~(부모)안에 있는 모든 자식
    
    ---
    
### 클래스 2개 이상 사용 시
-     <class=”클래스명1(띄어쓰기)클래스명2”;
   
    ---
    
### background 기능
![Untitled 7](https://github.com/kimhaaneul/study/assets/158141404/37251c30-e030-4e2d-9fad-00bfe15ee238)

    
    - url ../ : 상위 폴더로 이동하라는 뜻
    
 - 이게 margin collapse 현상(아래 이미지)<br>

![Untitled 9](https://github.com/kimhaaneul/study/assets/158141404/cc668f2f-183a-4046-8608-c732d8c86bcb)


- 이렇게 padding 값을 1px만 줘도(아래 이미지)<br>
![Untitled 10](https://github.com/kimhaaneul/study/assets/158141404/a2d55593-94dd-4def-b2a9-2464c84f8836)


- 원하는대로 나온다(아래 이미지)<br>
![Untitled 11](https://github.com/kimhaaneul/study/assets/158141404/84797b72-ec4d-4961-961a-ef829a02bcf7)


---

### position기능

-     position : relative;
    - 통째로 옮길수 있음. 좌표 이동 가능
    - 공중에 뜬다.
-     position : static; : 좌표이동X
-     position : fixed;
    - 현재 화면이 기준
    - 현재 화면을 기준으로 고정되는 요소가 필요할때 사용 (상단 메뉴 같은거 생각하면 편함)
-     position : absolute;
    - 내 부모 태그가 기준(클래스)
    
    ---
    
### 기본으로 적고 시작하면 좋은 태그들
    
![Untitled 12](https://github.com/kimhaaneul/study/assets/158141404/6fa60e01-aa05-4904-83f6-8ff4b94815aa)

    
 - 위 3개는 기본적으로 css에서 걸고 시작하면 편함
    
---
    
### input 태그
    
    - input type=”(스페이스바)” 하면 여러가지 기능들이 보임. 필요한거 맞춰서 쓰면 된다.
      
![Untitled 13](https://github.com/kimhaaneul/study/assets/158141404/a923cc4f-ef7a-4a73-9232-4c71daf3b043)

    
    - value = value에 적어진 값들이 보임
    - placeholder =”배경 글자”가 보임 ex)아이디를 입력하세요 이런거
    - name =”어떤 인풋인지?” 이름 적어주는 곳
    - submit =”전송” : 입력한 값을 전송하는 것
    - textarea : 큰 인풋을 만들수 있는 박스(드래그 해서 크기 늘릴 수 있음)
    - <select>+<option>
    
![Untitled 14](https://github.com/kimhaaneul/study/assets/158141404/8de260be-9bd8-4b1b-9a6d-6ccce8c13099)

    
- select 태그를 사용하고 안에 <option>태그를 사용하면
    
![Untitled 15](https://github.com/kimhaaneul/study/assets/158141404/cb6a13fd-b57e-4cfd-aedc-7d17afea7203)

    
- 이렇게 여러 옵션을 보여줄 수 있는 목록을 만들 수 있음
    

    
### table 만들기
    
-  테이블은 기본적으로 공간을 가지고 있음.
-     border-collapse : collapse :
    
 → 테이블의 공간을 없애주는 기능, 엄청 많이 사용되고 있음, 
    
- 먼저 css 상단에 달아두고 하는 경우도 많음
    
    -     body안에 <div>하나를 생성하고 <table></table>을 생성
    -     행(가로)<tr>
    -     열(세로)<td>
    
→ 순서는 반드시 tr을 먼저 열고 그 안에 td를 담아야 함.
    
→ td 태그 안에 p태그는 셀 안의 상하정렬 구현 가능.
    
-     제목 같은 진한 굵기를 주고 싶을떄 : th
    
### 분류를 위한 태그
    
-     thead : 제목 같은 걸 표현하기 위한 head(행) —> 따로 스타일 주기 좋음
-     tbody : 일반 행은 tbody안에 담으면 좋음

→ 기능상 차이는 없고 분류를 쉽게 하기 위해서 가끔 사용함 알아두면 좋음!

---
