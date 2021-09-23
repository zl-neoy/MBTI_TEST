### CHAPTER 1. 세렝게티 동물 테스트 제작하기

- 연결한 css가 bootstrap 밑에 있어야 부트스트랩을 변형하고 싶을 때 우리의 css가 덮어씌어짐.
- extention 설치 : live server.
- `<html lang="en">`이 있으면 영어로 인식하고 자동으로 번역해줄까? 물어봄. en이 아니라 ko로 바꾸기
- 적절한 간격 위해 `<body class = "container">` : 부트스트랩에서 그리드 시스템을 만들때 사용
- flex box : css를 이용해서 정렬을 할 때 사용되는 속성
- mbti 결정 로직 : 앞 쪽만 계산해서 과반수 이상이면 앞, 미만이면 뒤
- 변수를 만들어야 하는데 input타입을 hidden으로 => 총 변수 4개 필요.
- jquery를 안 써봐서 문법이 헷갈린다.
- 태그의 속성을 바꾸어 주는 attr
- `.html()` : 선택한 요소 안의 내용을 가져오거나, 다른 내용으로 바꾼다.

### CHAPTER 2. 서비스 고도화하기

(1) SNS 공유 기능 만들기

- AddThis라는 서비스 활용
- Share Buttons

(2) 광고 붙이기

- 애드 네트워크 이용(Google Adsense, KaKao Adfit)

(3) 광고 붙이기

(4) 네이버에서 내 사이트 검색되도록 하기

- 네이버 검색에 나오려면?
  - 네이버 웹 마스터 도구에 내 사이트 등록
  - 검색 관련 문서 제출
- 검색 엔진에는 크롤러라는 컴색 엔진이 있음(Naver-Yeti)
- robots.txt라는 문서(규정포함)를 보고 크롤링이 가능한지 여부 판단
- sitemap.xml(사이트 맵) : 크롤러가 좀 더 쉽게 내 사이트를 탐색할 수 있도록 도와줌

- Naver Search Advisor -> HTML 파일 업로드 -> 검증 -> robots.txt 다운로드. -> 작업 폴더에 넣기
- sitemap generator : <a>https://www.xml-sitemaps.com/</a>
  : URL을 등록하면 사이트를 스캔하며 sitemap.xml 파일을 생성해줌. -> View Sitemap Details -> download -> 작업 폴더에 넣기

(5) 검색엔진 최적화 (SEO)

- SEO : Search Engine Optimization
- SEO가 더 잘 되어있을 수록 상단에 노출
- 검색엔진 최적화
  - 내부 요소 최적화 (HTML, 컨텐츠, 메타태그 등)
  - 외부 요소 최적화 (백링크 개수 등)
- Naver Search Advisor의 진단하기를 통해 내 사이트가 얼마나 검색친화적인지 진단 가능
- 오픈 그래프 태그 : 내 사이트가 외부로 공유될 때 활용되는 태그
- SEO 최적화 위해 네이버 웹마스터 가이드 적극 참고
- 타이틀, 설명, 오픈 그래프 해놓음.

  (6) 서비스 완성하기 (디자인 에셋 활용)

### CHAPTER 3. Outro
