`<h1>~<h6> = <p class="h1"> ~ <p class="h6">`

* h1 스타일들과는 다르게 눈에 띄게 타이틀이 필요한 경우 - display heading 사용
```
<h1 class="display-1">Display 1</h1>
<h1 class="display-2">Display 2</h1>
<h1 class="display-3">Display 3</h1>
<h1 class="display-4">Display 4</h1>
```

<mark>highlight</mark> - 하이라이트 효과
<del>취소선</del>
<s>취소선?</s>
<ins>밑줄</ins>
<u>밑줄</u>
<small>작은글씨</small>
<strong>굵은글씨</strong>
<em>기울인글씨</em>


### Abbreviations - 약어, abbr 태그 사용 후 title을 추가하면서 도움말 노출
<abbr title="test">sssssssss</abbr>

<p><abbr title="HyperText Markup Language" class="initialism">HTML</abbr>ssssssss</p>

### Blockquotes - 인용문
- 인용문안에 footer 를 추가할 수 있음. 어디에서 인용했는지 출처 등을 표현 할 때 유용
<blockquote class="blockquote text-right">
test2222222ddkdkdkdkdkdkd
<footer class="blockquote-footer">누구누구가 말해씀 <cite title="cite test">xxxx책에서</cite></footer>
</blockquote>

### Alignment
```
<p class="text-right">오른쪽정렬</p>
<p class="text-left">왼쪽정렬</p>
<p class="text-center">가운데정렬</p>
```

### Lists
```
<ul class="list-unstyled">
//list-unstyled 클래스 추가 시 기본 세팅된 패딩과 list style 초기화
</ul>
```
```
<ul class="list-inline">
<li class="list-inline-item">111</li>
<li class="list-inline-item">222</li>
</ul>
```

## Code
### inline code
<code>&lt;section&gt;</code> ddddddddd

```
<code>&lt;section&gt;</code>
```
### code blocks
<pre>
<code>
code block test
test1
test3
test3
&lt;p&gt;p block &lt;/p&gt;
</code>
</pre>

### Variables
<var>variables</var> no  variables

### User input
<kdb>Ctrl</kdb>+<kdb>b</kdb>

### Sample output
<samp>sample output</samp> Sample output no tag