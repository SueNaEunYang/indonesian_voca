# Kartu Kata

공부하면서 모은 인도네시아어 단어를 플래시카드로 복습하는 웹앱. 파일 하나(`index.html`)로 돌아가고, 서버나 설치가 필요 없다.

- 단어 붙여넣기: 한 줄에 `단어 = 뜻` (`=`, ` - `, 탭, 쉼표 가능)
- 간격 반복: 알아 → 1·2·4·7·15·30·60일 뒤, 모름 → 같은 묶음 안에서 다시
- 방향 전환(인니어→뜻 / 뜻→인니어 / 섞어서), 브라우저 발음 듣기(id-ID)
- 기록은 브라우저 localStorage에 저장 — 기기를 옮길 땐 백업 파일로

## GitHub Pages 배포

1. 이 폴더를 GitHub 저장소로 올린다.
2. 저장소 Settings → Pages → Source: `Deploy from a branch`, Branch: `main` / `/ (root)`.
3. 1~2분 뒤 `https://<아이디>.github.io/<저장소이름>/` 에서 열린다.
