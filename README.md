# LUVERE Landing Site

GitHub Pages에 바로 올릴 수 있는 정적 랜딩페이지입니다.

## 포함 파일

- `index.html`: 랜딩페이지
- `thank-you.html`: CTA 클릭 후 전환 확인 페이지
- `assets/landing.png`: 피그마 시안 이미지

## GitHub Pages 배포 방법

1. GitHub에서 새 저장소를 만듭니다.
2. 이 폴더 안의 파일을 저장소에 업로드합니다.
3. 저장소의 `Settings` > `Pages`로 이동합니다.
4. `Build and deployment`에서 `Deploy from a branch`를 선택합니다.
5. Branch는 `main`, folder는 `/root`로 설정하고 저장합니다.
6. 몇 분 뒤 표시되는 GitHub Pages 주소로 접속합니다.

## 광고 소재 A/B 테스트용 링크 예시

소재별로 `utm_content` 값을 다르게 붙이면 어떤 소재에서 클릭이 발생했는지 구분하기 쉽습니다.

```text
https://사용자명.github.io/저장소명/?utm_source=meta&utm_campaign=luvere_ab_test&utm_content=creative_a
https://사용자명.github.io/저장소명/?utm_source=meta&utm_campaign=luvere_ab_test&utm_content=creative_b
```

현재 CTA는 `thank-you.html`로 이동합니다. 실제 구매 페이지가 생기면 `index.html`의 `thank-you.html` 링크를 결제 또는 상세 구매 URL로 바꾸면 됩니다.
