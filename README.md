# 청기와가든 GitHub Pages 홈페이지

첨부된 청기와가든 소개 자료와 로고·메뉴 이미지를 사용해 제작한 반응형 정적 홈페이지입니다.

## 폴더 구성

```text
cheonggiwa-garden-site/
├── index.html
├── README.md
└── assets/
    ├── styles.css
    ├── script.js
    └── images/
        ├── logo.png
        ├── oyster-stone-pot.webp
        ├── octopus-bossam.webp
        └── spicy-kaljebi.webp
```

## GitHub Pages 게시 방법

1. GitHub에서 새 저장소(repository)를 만듭니다.
2. 이 ZIP의 압축을 풀고, **폴더 안의 파일 전체**를 저장소 최상위에 업로드합니다. `index.html`이 저장소 첫 화면에 보여야 합니다.
3. 저장소의 **Settings → Pages**로 이동합니다.
4. **Build and deployment**에서 `Deploy from a branch`를 선택합니다.
5. Branch는 `main`, 폴더는 `/(root)`를 선택하고 **Save**를 누릅니다.
6. 잠시 뒤 표시되는 `https://사용자이름.github.io/저장소이름/` 주소에서 홈페이지를 확인합니다.

## 수정할 곳

- 본문과 사업자 정보: `index.html`
- 색상·레이아웃: `assets/styles.css` 상단의 `:root`
- 이미지: `assets/images/`의 파일을 같은 이름으로 교체
- 전화 링크: `index.html`에서 `0312252922` 검색
- 지도 링크: `index.html`에서 `map.naver.com` 또는 `google.com/maps` 검색

## 배포 전 확인 권장

- 메뉴명, 가격 및 실제 판매 여부
- 영업시간과 휴무일(현재 자료에 없어 사이트에 표시하지 않음)
- 주소, 전화번호, 대표자명, 사업자등록번호
- 네이버 지도 검색 결과가 정확한 매장을 가리키는지

## 기술 정보

- 순수 HTML/CSS/JavaScript로 제작되어 별도 빌드가 필요 없습니다.
- PC·태블릿·모바일 반응형 레이아웃을 지원합니다.
- 전화 연결, 이메일, 네이버 지도, Google 지도 링크가 포함되어 있습니다.
- 외부 폰트 로딩에 실패해도 시스템 기본 글꼴로 표시됩니다.
