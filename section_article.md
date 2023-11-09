# article과 section에 대해 알아보자

<br/>

1. section
```html
서로 관계 있는 문서를 분리하는 역할을 한다.
ex)
<article>
  <h2>사람</h2>
  <section>뚱뚱한 사람</section>
  <section>마른 사람</section>
<article>
```

<br/>

2. article
```html
article도 문서를 분리하는 역할을 한다.
하지만 조금 더 구체적인 의미를 가지고 있다고 보면 된다.
(내용이 독립적이고 스스로 설 수 있는 문서일때)
ex)
<section>
  <h2>글 모음</h2>
  <article>글 1</article>
  <article>글 2</article>
  <article>글 3</article>
</section>
```

3. 구별 하기
```
1) 내용이 독립적이고 스스로 설 수 있다면? article 태그
2) 내용이 서로 관계가 있으면서 분리하고 싶다면? section 태그
3) 의미적으로 관계가 없고 영역을 묶거나 나누고 싶다면 div 태그를 사용한다.
```
