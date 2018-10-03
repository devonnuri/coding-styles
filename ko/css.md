# CSS

솔직히 CSS보다는 SCSS를 주로 사용한다.

하지만 딱히 큰 차이는 없으니 CSS를 가지고 설명하도록 하겠다.

다음을 보면 된다.

```css
.div {
  /* 레이아웃 관련 프로퍼티 */
  display: block;
  margin: 0px;
  border: 1px solid gray;
  border-radius: 5px;
  
  /* 글자색, 배경색 등의 간단한 프로퍼티 */
  color: white;
  background-color: black;
  text-shadow: 2px 2px #ff0000;
  
  /* 트랜지션과 같은 기타 프로퍼티 */
  transition: 0.1s all;
}
```

## 수치 관련 설정

* `em`은 글자 관련 설정을 할 때 사용한다.
* `px`는 `border-size`, `border-radius` 등의 세밀한 설정에 사용한다.
* `rem`은 위의 설정을 제외한 전반적인 레이아웃 설정을 할 때 사용한다.
* 색상은 `#c0ffee`와 같이 소문자 16진수로 표현하는 것을 선호한다.
    * 하지만 투명도를 줘야 하는 상황이라면, `#c0ffee7f`와 같은 16진수보다 rgba를 선호한다.
