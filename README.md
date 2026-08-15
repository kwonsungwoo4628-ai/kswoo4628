# kswoo4628

웹 디자인(상세페이지 등) 작업을 Figma에서 진행하고, 그 내용을 문서로 정리해두는 저장소입니다.

## 구조

```
├── docs/                         공통 디자인 가이드
│   ├── design-system.md          컬러/타이포그래피/컴포넌트 규칙
│   └── figma-links.md            자주 쓰는 Figma 파일 링크 모음
├── projects/                     프로젝트별 폴더
│   └── _template/                새 프로젝트 시작 시 복사해서 사용
│       ├── README.md             프로젝트 개요/진행 상태
│       └── detail-pages/
│           └── _template.md      상세페이지 정리 템플릿
├── assets/                       최소한의 로컬 이미지 (원본 파일 X, 용량 주의)
└── .gitignore                    무거운 원본 디자인 파일 제외
```

## 새 프로젝트 시작하는 법

1. `projects/_template/` 폴더를 복사해서 `projects/[프로젝트명]/`으로 이름 변경
2. `README.md`에 개요 작성
3. 상세페이지 단위로 `detail-pages/` 안에 문서 추가 (`_template.md` 복사해서 사용)
4. 원본 디자인 파일은 로컬에 두지 말고 Figma 링크만 문서에 남기기 (용량 절약)
