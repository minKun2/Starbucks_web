# 스타벅스 코딩 시 배운 것 정리

## 목록

### 1. HTML

### 2. CSS

### 3. JS

=========================================================================================

### HTML

#### 1. 오픈 그래프

[오픈 그래프 이미지]

오픈 그래프란?
오픈 그래프는 링크를 다른 사람에게 공유를 했을 때, 미리보기 이미지, 제목, 설명 등 해당 링크의 대한 간단한 정보를 알려줍니다.
이러한 정보는 HTML에서 다룰 수 있으며 메타정보를 이용하여 작성이 가능합니다.

- 작성 예시

```html
<meta property="og:type" content="website" />
<meta property="og:site_name" content="github" />
<meta property="og:title" content="github korea" />
<meta
  property="og:description"
  content="깃허브는 분산 버전 관리 툴인 깃저장소 호스팅을 지원합니다."
/>
<meta property="og:image" content="./image/githubs_seo.jpg" />
<meta property="og:url" content="https://github.com" />
```

- `og:type` : 웹페이지 타입 (website, video.movie 등등)
- `og:site_name` : 웹사이트의 이름(URL과는 다릅니다.)
- `og:title` : 콘텐츠 제목
- `og:description` : 웹페이지의 간단한 설명 (제목 아래에 표시되며, 너무 길 경우 악성 페이지로 인식될 수 있습니다.)
- `og:image` : 링크 공유시 보여지는 이미지

  📘 SEO란?

  ➡️ Search Engine Optimization의 약자로, 검색 엔진 최적화를 제공합니다. 구글이나 네이버 등 자신의 웹 사이트를 노출할 수 있도록 정보를 최적화하는 작업을 말합니다.

- `og:url` : 웹 페이지 url

#### 2. 트위터 카드

[트위터 카드]

트위터 카드란?
위에서 본 오픈 그래프와 마찬가지로 웹사이트의 정보를 카드형식으로 미리보기 기능을 해주는 것입니다.

- 작성 예시

```html
<meta property="twitter:card" content="summary" />
<meta property="twitter:site" content="github" />
<meta property="twitter:title" content="github korea" />
<meta
  property="twitter:description"
  content="깃허브는 분산 버전 관리 툴인 깃저장소 호스팅을 지원합니다."
/>
<meta property="twitter:image" content="./image/githubs_seo.jpg" />
<meta property="twitter:url" content="https://github.com" />
```

- `twitter:card` : 페이지의 유형(summary, player)
- `twitter:site` : 사이트 이름
- `twitter:title` : 페이지 이름 (제목)
- `twitter:description` : 페이지 간단 설멸
- `twitter:image` : 페이지 대표 이미지 주소 (URL)
- `twitter:url` : 페이지 주소 (URL)

#### 3. 폰트 설정하기

[폰트 설정]

폰트를 설정하는 이유는 모든 브라우저에서 똑같은 폰트를 제공하기 위해서 폰트를 제공합니다.
Google fonts 등에서 폰트를 사용할 수 있습니다.

- 주의사항
- 폰트 사용 시 상업적/개인적 이용이 가능한 라이센스 확인 필수!!

설정법 [google fonts]

1. google fonts 진입 [google fonts](https://fonts.google.com/)
2. 사용할 서채 검색
   [사진1]
3. 사용할 방식 선택 link/import 방식
   [사진2]
4. css와 함께 파일에 적용
5. 확인

- 개발자 도구(F12) > body > Computed > font-family 값 확인
  [사진3]

#### 4. google Material Icons

현업에서 기본적으로 사용되는 아이콘들을 구글에서 제공함. (매번 디자이너에게 요청할 수 없기 때문에)
