# HTML 기능

### html의 주석 : 컨+물음표

-     HTML : Markup Language
- 자료가 어디에 어떻게 배치되어있나 표현하기 위한 언어
---

### 이미지 넣기
![Untitled 1](https://github.com/kimhaaneul/study/assets/158141404/74ba5099-94b5-47b2-864f-35695a300d0b)

-     img src=”./폴더/파일명.확장자”

→src는 ‘속성’이라고 부름

    - 링크 걸기
    - a href=”주소 입력”
### 버튼 만들기
![Untitled 3](https://github.com/kimhaaneul/study/assets/158141404/99a6df0f-8c4c-411b-8586-a284a58f29ab)
<button>보일 이름</button>

---

### 리스트 만들기
![Untitled 4](https://github.com/kimhaaneul/study/assets/158141404/c99c4709-48dc-460c-a4ea-1b302f9f89d1)
- 클래스 2개 이상 가능. 2개 이상 클래스 넣을 시

- ul : 리스트를 담아주는 하나의 주머니

- li 원하는 항목1

계속 추가 하면 늘어남!

---

### span 태그
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

### div태그

-     div 태그 : 네모난 박스라고 생각하면 된다.

-     display : block; —> 박스를 가운데로 정렬해 주는 기능.

- 기본으로 display기능을 가지고 있음.
  
  하지만 div는 기본으로 block 기능을 가지고 있어서 굳이 안 걸어도 됨.
<br>

-     display : block 뜻 —> 가로행을 전부 차지해주세요 라는 뜻.

- display 속성에 여러가지 들어있으니 보고 원하는거 쓰면 된다!
<br><br>

- 박스 안에 들어가면 자동으로 div의 css가 1순위가 된다.
  
- 자잘한 것들은 div class안에 원하는 style 값들을 넣어두는게 훨씬 깔끔하고 단순하게 할 수 있음.
  
- div 태그로도 테이블을 만들 수 있음
    -     div style=”display: table” 을 해주면 테이블 처럼 생김
    -     style= “display : table-row” : tr 태그랑 똑같은 기능
    -     style =” display : table-cell” : td랑 똑같은 태그

---


### nav바

-     nav :  div 와 똑같음, 하지만 div보다 읽기 쉬울 수 있음
-     section : div와 똑같음 = 웹페이지에서 큰 덩어리를 표현하고 싶을 떄 사용
-     footer : div와 똑같음 = 웹페이지에서 큰 덩어리를 표현하고 싶을 떄 사용

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
    
---
    
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

---

### 분류를 위한 태그
    
-     thead : 제목 같은 걸 표현하기 위한 head(행) —> 따로 스타일 주기 좋음
-     tbody : 일반 행은 tbody안에 담으면 좋음

→ 기능상 차이는 없고 분류를 쉽게 하기 위해서 가끔 사용함 알아두면 좋음!

---
<br><br>

## 다양한 텍스트 입력

### hn 제목 /hn

- <hn>태그에서 h는 제목을 뜻하는 heading을 줄인 말
  
- n의 자리에는 1~6의 숫자가 들어가며 제목 텍스트를 크기별로 표시할 수 있음
  
- h1이 가장 큰 제목이고 h2, h3···h6의 순서로 작아짐

<h1>지금 이게 h1이지롱</h2>
<h2>지금 이게 h2이지롱</h2>
<h3>지금 이게 h3이지롱</h3>
<h4>지금 이게 h4이지롱</h4>
<h5>지금 이게 h5이지롱</h5>
<h6>지금 이게 h6이지롱</h6>
<br><br>


### p택스트 단락, 줄 바꿈br

-     p 내용입력 /p
<br>

#### br태그와 p 태그의 차이점은?
- br태그를 두 번 사용하면 빈 줄이 생기면서 텍스트 단락이 나뉜 것처럼 화면에 표시할 수 있음.
  
  하지만 실제로는 단락이 만들어 진 게 아니므로 css를 사용해 텍스트 단락 스타일을 적용할 때 문제가 생긴다.
  
  따라서 텍스트 단락을 만들 때는 p태그를 사용해야 함.

---

### 인용할 때 쓰는 blockquote태그

- 다른 사람의 말이나 책의 내용을 인용할 때 흔히 큰 따옴표(” “)를 사용해 표시한다.
  
- 웹 브라우저에서는 이렇게 표시한 인용문을 인식할 방법이 없기 때문에

        <blockquote>들어갈 내용 입력</blockquote>

  로 인용문을 감싸주어야 함.
    
- 그러면 웹 브라우저는 blockquote태그 안에 내용을 인용문으로 알고 다른 텍스트보다 약간 들여서 보여줌.
  
  화면 낭독기에서 웹 문서를 읽어 내려가도 blockquote태그 안의 내용을 다른 텍스트와 구분함

---

### 텍스트를 굵게 표시하려면 strong, b태그

-     <strong>굵게 강조할 텍스트</strong>

-     <b>굵게 표시할 텍스트</b>

#### 두 태그는 눈으로 볼 때 별로 차이가 느껴지지 않지만 그래도 구분하는 이유는?

- 화면 낭독기의 기능 때문이다. 
    

---

### 기울인 텍스트를 입력해주는 em, i태그

-     <em>이탤릭체로 강조할 텍스트</em>

-     <i>이탤릭체로 표시할 텍스트</i>

#### em

- em : 강조를 뜻하는 emphasis의 줄임말
  
- em태그는 문장에서 흐름 상 특정 부분을 강조하고 싶을때 사용
  
- 쉽게 말하면 문장에서 특별히 강조하고 싶은 부분에 사용

### i

- i : 이탤릭체, 기울기체를 뜻하는 (italic)의 줄임말
  
- i태그는 마음속의 생각이나 용어, 관영구 등에 사용
  
- 쉽게 말하면 다른 텍스트와 구별하기 위해 기울여서 표시하고 싶을 때 사용

---

## 그 외 텍스트 관련 태그들

### abbr

줄임말을 표시하고 title 속성을 함께 사용할 수 있음

-     <abbr title=”Internet of Things”>Iot</abbr>

---

### cite

웹 문서나 포스트에서 참고 내용을 표시함


p내가 경험한 가장 흥미진진한 일을 누군가를 만나는 일이다
-     영화, <cite>’비포선셋’</cite> 중</p>

---

### code

컴퓨터 인식을 위한 소스 코드


-     <code>function savetheLocal()</code>

---

### small

부가 정보처럼 작게 표시해도 되는 텍스트


-     <p>가격 : 13,000원 <small>(부가세 별도)</small></p>

---

### sub

아래 첨자를 표시함


-     <p>물의 화학식은 H<sub>2</sub>0입니다</p>

---

### sup

위 첨자를 표시함


-     <p>E = mc<sup>2</sup></p>

---

### s

취소선을 표시함

-     <p><s>34,000원</s>19,000원</p>

---

### u

밑줄을 표시함


-     <u>텍스트에 단순히 밑줄을 그어줌</u>


---

### ins

공동 작업 문서에서 새로운 내용을 삽입

-     <ins>새로운 내용을 삽입합니다.</ins>

---

### del

공동 작업 문서에서 기존 내용을 삭제

-     <del>기존 내용을 삭제함</del>

---
