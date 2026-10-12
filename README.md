# 디지랩 EVO

디지몬 스토리 사이버 슬루스 / 해커즈 메모리 진화 경로 탐색 도우미 (비공식 팬 사이트).

- 정적 사이트입니다. `index.html`을 웹 서버(GitHub Pages 등)로 열면 됩니다.
- 구글 로그인과 경로 저장은 `firebase-config.js`에 Firebase 웹앱 설정값을 넣어야 켜집니다.
- Firestore 규칙: `match /digilabRoutes/{uid} { allow read, write: if request.auth.uid == uid; }`
