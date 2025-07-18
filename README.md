# Multi-Module-Practice
Android 멀티모듈 연습
```markdown
MultiModulePractice/
├── app/                    # 메인 앱 모듈
├── core/
│   ├── common/            # 공통 유틸리티, Extension
│   ├── ui/                # 공통 UI 컴포넌트, 테마
│   ├── designsystem/      # 디자인 시스템
│   ├── data/              # Repository, DataSource
│   ├── domain/            # UseCase, Entity
│   ├── network/           # API, 네트워크 관련
│   ├── database/          # Room, 로컬 DB
│   └── navigation/        # 네비게이션 관련
├── feature/
│   ├── auth/              # 로그인, 회원가입
│   ├── home/              # 홈 화면
│   ├── profile/           # 프로필
│   ├── search/            # 검색
│   └── settings/          # 설정
└── build-logic/           # 빌드 로직, 컨벤션 플러그인
```
