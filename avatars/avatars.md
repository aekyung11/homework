# 아바타 과제

## HTML

```html
<main>
  <div class="avatar-row">
    <div class="avatar-frame">
      <img class="avatar" />
      <div class="status"></div>
    </div>
    <div class="avatar-frame">
      <img class="avatar" />
      <div class="status active"></div>
    </div>
    ...
  </div>
  <div class="avatar-row male">
    <!-- female과 같은 구조 -->
  </div>
</main>
```

## CSS

css는 float를 이용하여 원하는대로 표현되도록 설계했다.
그 후

```css
@supports (display: flex) {
  main {
    display: flex;
    flex-flow: column-reverse nowrap;
  }
  ...;
}
```

위 코드를 입력해 flex가 지원되는 환경애서는 avatar 순서가 반대로 보이도록 설계했다.
