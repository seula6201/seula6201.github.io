<!-- 
  ※ 제출 전 확인사항
  1. 해당하는 과제 섹션 하나만 남기고 나머지는 모두 삭제하세요.
  2. PR 제목 형식: [work01] 홍길동
  3. base: main / compare: gh-pages 로 설정되어 있는지 확인하세요.
-->

---

## [work01] 환경 설정 및 설치

> 가이드: `01-setup.md`

**배포 URL**
https://[내 GitHub ID].github.io

**완료한 작업**
- [ ] 학과 저장소 Fork 완료
- [ ] 저장소 이름을 `[내 GitHub ID].github.io`로 변경
- [ ] `dev` 브랜치 생성 (main 기준)
- [ ] `gh-pages` 브랜치 생성 (dev 기준)
- [ ] `dev` 브랜치에서 `_config.yml`의 `url` 수정
- [ ] `dev` → `gh-pages` merge 완료
- [ ] GitHub Pages 배포 브랜치를 `gh-pages`로 설정
- [ ] 배포 URL 접속 확인 (Actions 탭 초록색 체크)

**문제가 있었다면 적어주세요**
(없으면 삭제)

---

## [work02] 기본 설정 1 — Codespace 활용

> 가이드: `02-config.md`

**배포 URL**
https://[내 GitHub ID].github.io

**Codespace 이름**
(예: urban-disco-abc1234)

**완료한 작업**
- [ ] Codespace 생성 및 접속 확인
- [ ] `_config.yml` — `title`, `email`, `description`, `author` 수정
- [ ] `_config.yml` — `url` 본인 GitHub 주소로 수정 확인
- [ ] `_data/settings.yml` — 소셜 미디어 링크 설정
- [ ] `_data/settings.yml` — 헤더 로고 및 푸터 텍스트 설정
- [ ] `dev` → `gh-pages` merge 및 배포 확인

**문제가 있었다면 적어주세요**
(없으면 삭제)

---

## [work03] 기본 설정 2 — 로컬 작업 활용

> 가이드: `02-config.md`

**배포 URL**
https://[내 GitHub ID].github.io

**로컬 환경 버전 기록**

| 항목 | 버전 |
|------|------|
| Ruby | (예: 3.2.2) |
| gem | (예: 3.4.10) |
| Jekyll | (예: 4.3.2) |
| Bundler | (예: 2.4.10) |

**완료한 작업**
- [ ] Ruby 설치 및 버전 확인 (`ruby -v`)
- [ ] gem 버전 확인 (`gem -v`)
- [ ] Jekyll, Bundler 설치 (`gem install jekyll bundler`)
- [ ] 저장소 clone 및 `bundle install`
- [ ] 로컬 서버 실행 확인 (`bundle exec jekyll serve`)
- [ ] `_config.yml` — Disqus shortname 설정 (`disqus_shortname`)
- [ ] `_config.yml` — Formspree 엔드포인트 설정 (`formspree_endpoint`)
- [ ] `_data/settings.yml` — 라이트/다크 모드 기본값 설정
- [ ] `dev` → `gh-pages` merge 및 배포 확인

**문제가 있었다면 적어주세요**
(없으면 삭제)

---

## [work04] 섹션 구성

> 가이드: `03-sections.md`

**배포 URL**
https://[내 GitHub ID].github.io

**완료한 작업**
- [ ] `index.html` — 표시할 섹션 목록 설정
- [ ] `index.html` — 섹션 순서 조정
- [ ] `_data/navigation.yml` — 네비게이션 메뉴 구성
- [ ] `_data/ui-text.yml` — UI 텍스트 한국어로 변경
- [ ] `dev` → `gh-pages` merge 및 배포 확인

**선택한 섹션 순서**
(예: hero-image → skills → portfolio → resume → blog → contacts)

**문제가 있었다면 적어주세요**
(없으면 삭제)

---

## [work05] 기본 섹션 콘텐츠 작성

> 가이드: `04-content.md`

**배포 URL**
https://[내 GitHub ID].github.io

**완료한 작업**
- [ ] `_data/content.yml` — hero 섹션 (이름, 소개글, 버튼) 수정
- [ ] `_data/content.yml` — services 섹션 (핵심 역량 3개 이상) 작성
- [ ] `_data/content.yml` — skills 섹션 (기술 스택 및 숙련도) 작성
- [ ] `_data/content.yml` — contacts 섹션 (연락처 정보) 작성
- [ ] 프로필 이미지 `assets/img/`에 업로드 및 hero 섹션에 적용
- [ ] `dev` → `gh-pages` merge 및 배포 확인

**문제가 있었다면 적어주세요**
(없으면 삭제)

---

## [work06] 이력서 섹션

> 가이드: `05-resume.md`

**배포 URL**
https://[내 GitHub ID].github.io

**완료한 작업**
- [ ] `_data/content.yml` — resume 섹션 학력 항목 작성
- [ ] `_data/content.yml` — resume 섹션 경력/활동 항목 작성 (3개 이상)
- [ ] 수치·성과 중심으로 설명 작성
- [ ] `dev` → `gh-pages` merge 및 배포 확인

**작성한 경력/활동 항목**
(예: 보안 동아리 팀장, 교내 CTF 대회 참가, 정보처리기능사 취득 등)

**문제가 있었다면 적어주세요**
(없으면 삭제)

---

## [work07] 포트폴리오 항목 관리

> 가이드: `06-portfolio.md`

**배포 URL**
https://[내 GitHub ID].github.io

**완료한 작업**
- [ ] `_works/` 폴더에 작품 파일 1개 이상 생성
- [ ] 각 작품에 제목, 카테고리, 썸네일 이미지 설정
- [ ] 작품 설명 작성 (배경 → 문제 → 내가 한 일 → 결과)
- [ ] `_data/settings.yml` — 포트폴리오 카테고리 필터 설정
- [ ] `dev` → `gh-pages` merge 및 배포 확인

**등록한 작품 목록**
- 

**문제가 있었다면 적어주세요**
(없으면 삭제)

---

## [work08] 블로그 포스트 작성

> 가이드: `07-blog.md`

**배포 URL**
https://[내 GitHub ID].github.io

**완료한 작업**
- [ ] `_posts/` 폴더에 포스트 파일 1개 이상 생성 (`YYYY-MM-DD-제목.md` 형식)
- [ ] Front Matter 작성 (layout, title, date, category, image, author, tags)
- [ ] 본문 마크다운으로 작성 (코드 블록 포함)
- [ ] 카테고리 및 태그 설정
- [ ] `dev` → `gh-pages` merge 및 배포 확인

**작성한 포스트 제목**
- 

**문제가 있었다면 적어주세요**
(없으면 삭제)

---

## [work09] 디자인 커스터마이징

> 가이드: `08-design.md`

**배포 URL**
https://[내 GitHub ID].github.io

**완료한 작업**
- [ ] `_sass/luique/setting.scss` — 포인트 색상(`$active_color`) 변경
- [ ] `_sass/luique/setting.scss` — 폰트 변경 (선택사항)
- [ ] Google Fonts 적용 (선택사항)
- [ ] 라이트/다크 모드 양쪽에서 확인
- [ ] 모바일에서 레이아웃 확인
- [ ] `dev` → `gh-pages` merge 및 배포 확인

**변경한 디자인 요소**
(예: 포인트 색상 #3498db으로 변경, Noto Sans KR 폰트 적용 등)

**문제가 있었다면 적어주세요**
(없으면 삭제)

---

## [work10] 최적화 및 마무리

> 가이드: `09-optimize.md`

**배포 URL**
https://[내 GitHub ID].github.io

**완료한 작업**

콘텐츠 확인
- [ ] hero 섹션 자기소개가 명확하고 완성도 있음
- [ ] 포트폴리오 작품 3개 이상 등록
- [ ] 이력서 섹션 학력/경력 작성 완료
- [ ] 블로그 포스트 2개 이상 작성

기술 확인
- [ ] 모든 이미지 정상 로딩
- [ ] 네비게이션 링크 정상 동작
- [ ] 모바일 레이아웃 확인
- [ ] 라이트/다크 모드 양쪽 확인

SEO 및 최적화
- [ ] `_config.yml` — `title`, `description` 최종 확인
- [ ] SEO 메타태그 설정
- [ ] 사이트맵 생성 확인 (선택사항)
- [ ] Google Analytics 연동 (선택사항)

최종 배포
- [ ] `dev` → `gh-pages` merge 및 최종 배포 확인
- [ ] 전체 사이트 오타·링크 최종 점검 완료

**최종 소감 한 줄**

**문제가 있었다면 적어주세요**
(없으면 삭제)