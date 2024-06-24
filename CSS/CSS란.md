# CSS

### css란? —>  Casscading Style Sheet : 스타일 보관파일

    css의 주석 처리 : 컨+물음표

- html에서 css link 거는 법
    
   ![Untitled](https://github.com/kimhaaneul/study/assets/158141404/613b5f15-14ff-423d-a7b0-56cd85286b07)

-     head태그 안에 <link>태그를 열어서 href 속성에 css파일 경로(상대경로)를 넣어주면<br>
      html에 css파일의 경로가 연결되어 사용이 가능해진다.

-     rel  : stylesheet 걸어 두기

---

### css 파일 생성하고 스타일 넣는 방법

![Untitled 1](https://github.com/kimhaaneul/study/assets/158141404/106b3d60-a121-441d-9207-b6332d888107)


- html에서 길게 걸려있는 style들만 뜯어와서 css에 중괄호 안에 넣기.
- 이렇게 중괄호 {} 안에 묶인 걸 클래스라고 함.

![Untitled 2](https://github.com/kimhaaneul/study/assets/158141404/7e3f04c6-e618-4f14-8589-51f68f3eca99)


- 그리고 이름은 .name~머대충 짓고나서 class로 불러오면 된다.

---

### 알아두면 그냥 좋은 거

    .이름암거나 { font-size : 20px } —→ 앞에 .붙고 묶인 걸 클래스라고 함

    #이름암거나 { font-size : 20px } —> 앞에 #붙고 묶인 걸 아이디라고 함

    p { font-size : 20px } —> 앞에 h3, h2, p…이렇게 태그 자체를 걸면 해당 태그 전체가 스타일이 들어감.

- 보통 id = 는 잘 사용하지 않음

---

### css 우선순위(셀렉터의 우선순위)

-     style : 1000점
-     id(100점
-     .class(10점)
-     p(점)

서로 얽히면 우선순위가 먼저 높은 순위로 겹쳐서 적용이 된다.

---

### container
- 여러 레이아웃들을 싸매는 박스
<br><br>

**div끼리 옆으로 붙이고 싶을때**

-     float: left; : 요소를 붕 띄워서 왼쪽 정렬
-     float 쓰고나서 다음에 온느 요소는 clear 주는게 좋음.
-     fotter같은 하단의 div만들 경우, 전에  float를 사용했다면 우선순위 때문에 안 먹는 경우가 있어서 clear : both;를 해주면 거의 풀림
-     display:inline-block : 내 크기만큼 차지해주세요

---

### button(btn) 들의 기능

![Untitled 3](https://github.com/kimhaaneul/study/assets/158141404/7221195c-315e-45d6-8be0-6a4ccbe8f952)


- 순서는 꼭
-     1. hover
-     2. focus
-     3. active
    
    → 이 순서로 해야함.

---
