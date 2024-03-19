# <form> 태그의 autocomplete 속성을 알아보자.

<br />

```
<form> 태그의 autocomplete 속성은 <form> 요소에서 자동 완성 기능을 사용할지 여부를 명시한다.
autocomplete 속성값을 on으로 명시하면,
브라우저는 사용자가 이전에 입력했던 값들을 기반으로 사용자가 입력한 값과 비슷한 값들을 드롭다운 옵션으로 보여준다.

이 속성을 사용하면 <form> 요소에서는 자동 완성 기능을 사용하면서 특정 <input> 요소에서는 자동 완성 기능을 사용하지 않거나 그 반대로 설정하는 것도 가능하다.
```

<br />

```html
<form autocomplete="on|off">

<form action="/examples" autocomplete="off">
  이름 : <input type="text" name="st_name"><br>
  학번 : <input type="text" name="st_id"><br>
  학과 : <input type="text" name="department"><br>
  <input type="submit">
</form>
```
