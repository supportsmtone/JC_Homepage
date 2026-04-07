# JC Homepage

JC 프라이빗 룸 소개용 정적 홈페이지입니다. **메인 페이지는 저장소 루트의 `index.html`** 입니다.

## 공개 주소 (커스텀 도메인)

- **https://playjc.co.kr/**

GitHub Pages에 `CNAME` 파일로 `playjc.co.kr` 을 지정해 두었습니다. 저장소 **Settings → Pages → Custom domain** 에도 동일하게 `playjc.co.kr` 을 입력하고 **Enforce HTTPS** 를 켜 주세요.

### DNS 설정 (도메인 등록업체)

**루트 도메인 `playjc.co.kr`** 을 GitHub Pages에 연결할 때는 아래 **A 레코드 4개**를 등록합니다. (값은 [GitHub 문서](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site#configuring-an-apex-domain) 기준입니다.)

| 유형 | 이름/호스트 | 값 |
|------|-------------|-----|
| A | `@` (또는 비움) | `185.199.108.153` |
| A | `@` | `185.199.109.153` |
| A | `@` | `185.199.110.153` |
| A | `@` | `185.199.111.153` |

**www 서브도메인** 을 쓸 경우 예: `www` → CNAME `supportsmtone.github.io` (GitHub 안내에 맞게 조정).

변경 후 전파까지 수분~최대 24시간 걸릴 수 있습니다.

## 로컬에서 보기

```bash
python3 -m http.server 5500
```

브라우저에서 [http://localhost:5500/](http://localhost:5500/) 로 접속합니다 (`index.html` 이 기본으로 열립니다).

## GitHub Pages (저장소 기본 URL)

커스텀 도메인 없이 볼 때: `https://supportsmtone.github.io/JC_Homepage/`

## 구성 파일

| 파일 | 설명 |
|------|------|
| `index.html` | 메인 랜딩 (네비, 히어로 영상, 룸·메뉴·위치) |
| `CNAME` | 커스텀 도메인 `playjc.co.kr` (GitHub Pages용) |
| `6인실.jpeg` ~ `14인실.jpeg` | 룸 이미지 |
| `멋진_남자들의_놀이터_영상_제작.mp4` | 히어로 배경 영상 |
| `명함_인쇄용_시안.html` | 명함 시안 (QR → playjc.co.kr) |

KakaoTalk으로 받은 추가 사진은 보관용으로 두었으며, 메인 페이지에서는 사용하지 않습니다.

## 라이선스

사이트 내용·이미지·영상의 저작권은 사업자에게 있습니다.
