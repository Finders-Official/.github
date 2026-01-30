# .github

Finders 조직의 GitHub 프로필 및 공용 설정을 관리하는 저장소입니다.

## Structure

```
.github/
├── profile/
│   ├── README.md          ← GitHub 조직 프로필에 표시되는 메인 README
│   └── assets/
│       ├── logo.png       ← Finders 로고
│       ├── banner.png     ← 배너 이미지 (디자이너 전달 후 추가)
│       └── team/          ← 팀원 프로필 사진 (naming: {romanized-name}.jpg)
└── README.md              ← 이 파일 (저장소 설명용)
```

## Banner Spec

디자이너에게 전달할 배너 규격:

| 항목 | 값 |
|:-----|:---|
| 사이즈 | **1280 x 320px** (4:1) |
| 포맷 | PNG |
| 브랜드 컬러 | `#E94E16` |
| 배경색 | `#131313` |
| 파일 크기 | 1MB 이하 |

배너 수령 후 `profile/assets/banner.png`에 저장하고, `profile/README.md` 상단의 배너 주석을 해제하세요.

## Team Photo Naming

팀원 사진은 `profile/assets/team/` 디렉토리에 로마자 표기로 저장합니다:

```
kim-deokhwan.jpg
lee-seungjoo.jpg
...
```
