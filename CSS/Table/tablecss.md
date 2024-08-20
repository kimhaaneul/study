### table 바깥 테두리 없애기
```
border: none; / 먼저 전체 테두리 없애버리고
```
```
border: 1px solid #333; / 각 셀에 선을 주고
```
```
.(테이블 id,혹은 class 입력) th:first-child,
.(테이블 id,혹은 class 입력) td:first-child{
    border-left: none; / 왼쪽 선 제거
}
```
```
.(테이블 id,혹은 class 입력) th:first-child,
.(테이블 id,혹은 class 입력) td:first-child{
    border-right: none; / 오른쪽 선 제거
}
```

