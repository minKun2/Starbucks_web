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
- `go:title` : 콘텐츠 제목
- `og:description` : 웹페이지의 간단한 설명 (제목 아래에 표시되며, 너무 길 경우 악성 페이지로 인식될 수 있습니다.)
- `og:image` : 링크 공유시 보여지는 이미지

  📘 SEO란?

    ➡️ Search Engine Optimization의 약자로, 검색 엔진 최적화를 제공합니다. 구글이나 네이버 등 자신의 웹 사이트를 노출할 수 있도록 정보를 최적화하는 작업을 말합니다.

- `og:url` : 웹 페이지 url
