# Resource

- 각종 이미지나 Policy 를 모아 놓은 공개 repo. 이미지를 Firestore 에 등록하거나 웹에 등록하기 어려운 경우가 있다. Firestore 에 등록하면 토큰이 사라지거나 이상하게 preview 가 안되는 경우가 발생한다. 또한 FF 의 경우, 임의의 이미지(파일)를 서버에 deploy 하기가 어렵다.

- Repository 주소: https://github.com/thruthesky/res
  - 이미지 주소: https://github.com/thruthesky/res/img
  - Policy 주소: https://raw.githubusercontent.com/thruthesky/res/main/policy/



# Image

- `/img` 폴더에 각종 이미지를 저장한다.

# Policy

- `/policty` 폴더에 각종 정책을 모아서 URL 로 오픈하는 Repo. 정책은 단순히 약관이나, 개인정보 보호 외에도, 결제와 관련된 금액, 환불 등의 모든 정책이 다 포함된다.

홈페이지: [ <a href="https://github.com/thruthesky/policy">Policy repo https://github.com/thruthesky/policy</a> ]에 접속하면, 어떤 정책 파일들이 만들어져 있는지 보고 참고 할 수 있다.

## 사용 URL

- URL 을 짧게 쓰기 위해서 `https://thruthesky.github.io/policy/xxxx-xxxx-xx.txt` 와 같이 쓰면 된다.
  - Github URL `https://raw.githubusercontent.com/thruthesky/policy/main/xxxx-xxxx-xx.txt` 와 같이 긴 URL 을 쓰지 않는다.

## 형식

파일 형식 지정

## 개인정보 보호 정책, Privacy Policy

- `[도메인]-privacy-[ln].txt`


위에서 `도메인` 에는 `withcenter`, `philgo`, `sonub` 와 같이 extension 은 빼고 입력. 앱 이름을 입력해도 된다.
`ln` 에는 두 자리 국가 코드를 입력한다.

예) `sonub-privacy-en.txt`
## 가입약관 - Terms and Use

- `[도메인]-terms-[ln].txt`

위에서 `도메인` 에는 `withcenter`, `philgo`, `sonub` 와 같이 extension 은 빼고 입력. 앱 이름을 입력해도 된다.
`ln` 에는 두 자리 국가 코드를 입력한다.

예) `sonub-terms-ko.txt`

## 기타 정책

- `[도메인]-[기타-정책-코드]-[ln].txt`

예)
- `sonub-in-app-purchase-policy-ko.txt`
- `sonub-in-app-purchase-policy-en.txt`


## 이미 만들어진 목록 예

- <a href="./sonub-privacy-ko.txt">Sonub Privacy</a>

