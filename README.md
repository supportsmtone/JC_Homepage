# JC Homepage

JC 프라이빗 룸 소개용 정적 홈페이지입니다. 룸 안내, 주류·배달 안내, 지도, 예약 전화 링크가 포함되어 있습니다.

## 로컬에서 보기

```bash
python3 -m http.server 5500
```

브라우저에서 [http://localhost:5500/](http://localhost:5500/) 로 접속합니다.

## GitHub Pages로 배포

1. 저장소 **Settings → Pages** 로 이동합니다.
2. **Build and deployment** 에서 Source를 **Deploy from a branch** 로 선택합니다.
3. Branch를 **main** (또는 사용 중인 기본 브랜치)으로, 폴더는 **/ (root)** 로 지정 후 Save 합니다.
4. 몇 분 뒤 다음 주소에서 사이트가 열립니다:  
   `https://supportsmtone.github.io/JC_Homepage/`

## 구성 파일

| 파일 | 설명 |
|------|------|
| `index.html` | 메인 랜딩 (네비, 히어로 영상, 룸·메뉴·위치) |
| `6인실.jpeg` ~ `14인실.jpeg` | 룸 이미지 |
| `멋진_남자들의_놀이터_영상_제작.mp4` | 히어로 배경 영상 |
| `명함_인쇄용_시안.html` | 명함 시안 (별도 페이지) |

KakaoTalk으로 받은 추가 사진은 보관용으로 두었으며, 메인 페이지에서는 사용하지 않습니다.

## 라이선스

사이트 내용·이미지·영상의 저작권은 사업자에게 있습니다.
