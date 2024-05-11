# 네이버 과제

## HTML

구조는 다음과 같다
![naver과제_구조](https://github.com/aekyung11/homework/assets/61109672/34581ce2-ae6e-464d-8bbc-496b3d6c6d28)

![naver과제_구조2](https://github.com/aekyung11/homework/assets/61109672/345b784d-622e-47bb-b548-c609f1196e27)

```html
<div class="naver-form">
  <h1>
    <img <!-- logo -- />
    />
  </h1>
  <form action="/" class="login-form">
    <fieldset>
      <legend class="sr-only">로그인 폼</legend>
      <div role="group" class="form-input">
        <label class="sr-only" for="userId">아이디</label>
        <input <!-- id -- />
        />
      </div>
      <div role="group" class="form-input">
        <label class="sr-only" for="userPwd">비밀번호</label>
        <input <!-- pw -- />
        />
      </div>
      <button type="submit" class="login-button button">로그인</button>
    </fieldset>
    <div class="additional-function">
      <div class="maintain-login-status">
        <input <!-- btn -- />
        />
        <label for="saveLoginInformation">로그인 상태 유지</label>
      </div>
      <a href="" target="_blank" class="ip-security">IP 보안</a>
    </div>
  </form>
</div>
```
