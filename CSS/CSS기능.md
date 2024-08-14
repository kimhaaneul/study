### 박스에 그림자 넣기

- box-shadow: 5px(가로) 5px(세로) 5px(번짐) -5px(그림자크기+,- 다 가능) #fff(색상);

![Untitled 5](https://github.com/kimhaaneul/study/assets/158141404/fb315e24-599e-4729-8ece-50125ef32956)


이렇게 원하는 값으로 넣어주면 된다

![Untitled 6](https://github.com/kimhaaneul/study/assets/158141404/0aa72b93-097c-4278-b837-6c95a953171a)


적용된 모습!!

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

### js에서 마치 애니메이션 효과같은 기능 사용 시
```
display:none; --> visibility : hidden;
: 애니메이션 효과 줄때 쓰는거, display:none이랑 같음
```
```
display:black --->  visibility: visible;
: 애니메이션 효과 줄때 쓰는거, display:black랑 같음
```

### 버튼 배경 투명하게(만든 이미지를 사용할 때)
```
background-color: transparent;
```







