*공식홈페이지*
https://getbootstrap.com/docs/4.4/getting-started/introduction/

20200403 기준 최신 버전 4.4.x

공식홈페이지에 설치방법 및 시작템플릿이 있음. 


## containers
* breakpoint는 sm, md, lg, xl 
.container - 설정된 breakpoint의 max-width !이게 default conteiner all in one
.container-fluid - 모든 breakpoint에서  width: 100%
.container-{breakpoint}

ex) 각 픽셀은 예시 사이즈고 기종별 최대 커트라인을 수정하면 됨. 
|                  | extra small <576px | small >= 576px | medium >= 798px | large >= 992px | extra large >= 1200px |
| ---------------- | ------------------ | -------------- | --------------- | -------------- | --------------------- |
| .container       | 100%               | 540px          | 720px           | 960px          | 1140px                |
| .container-sm    | 100%               | 540px          | 720px           | 960px          | 1140px                |
| .container-md    | 100%               | 100%           | 720px           | 960px          | 1140px                |
| .container-lg    | 100%               | 100%           | 100%            | 960px          | 1140px                |
| .container-xl    | 100%               | 100%           | 100%            | 100%           | 1140px                |
| .container-fluid | 100%               | 100%           | 100%            | 100%           | 100%                  |

- 그리드에서 모든 col은 gutter 영역이라고 패딩이 들어가있는데 이 패딩을 사용안할거라면 .row 클래스에 .no-gutters 클래스를 추가 

* row 하나 안에서 모든 col을 동일하게 여러줄 만들 때
```
<div class="container">
  <div class="row">
    <div class="col">col</div>
    <div class="col">col</div>
    <div class="w-100"></div>
    <div class="col">col</div>
    <div class="col">col</div>
  </div>
</div>
```

* row에서 col 숫자구분없이 동일하게 .col만 쓰되 한줄에 나올 갯수는 지정하고싶을 때 .row-cols-{갯수} 지정
```
<div class="container">
  <div class="row row-cols-3">
    <div class="col">Column</div>
    <div class="col">Column</div>
    <div class="col">Column</div>
    <div class="col">Column</div>
  </div>
</div>
```

## Alignment
1) Vertical
상단정렬 - .align-items-start, .align-self-start
중간정렬 - .align-items-center, .align-self-center
하단정렬 - .align-items-end, -align-self-end

2) Horizontal
왼쪽정렬 - .justify-content-start 
가운데정렬 - .justify-content-center
오른쪽정렬 - .justify-content-end
중간간격이 적당히 빈채로 정렬 - .justify-content-around
양 사이드로 정렬 - .justify-content-between