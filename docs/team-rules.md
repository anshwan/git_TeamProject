# 팀 규칙

## 이슈 규칙

- **모든 변경은 반드시 이슈와 연결**
- **이슈 예시**

  ```
  - README 메인 페이지 작성
  - 팀 규칙 문서 작성
  - 팀원 자기소개
  ```

## 커밋 컨벤션

- **커밋 메시지 형식**

  ```
  [# 이슈 번호] 작업 설명
  ex)
  [#1] feat: README 파일 작성
  [#5] fix: 자기소개 파일 오타 수정
  ```

- **type 별 설명**
  - feat : 새로운 기능 추가
  - fix: 버그 수정
  - docs: 문서 수정
  - style: 코드 스타일 수정
  - refactor: 코드 리팩터링
  - test: 테스트 추가/수정
  - build: 빌드 수정
  - chore: 기타 수정

## 브랜치 전략

- **main 직접 push ❌**

- **모든 작업은 feature branch 에서 진행**

- **main 반영은 PR 통해서만 하기**

- **PR 머지하기 전에 리뷰 한번씩 해주기**

- **브랜치 이름 예시**
  ```
  feature/<이슈번호>-<작업명>
  ex)
  feature/3-introduce
  feature/7-rule-document
  ```
