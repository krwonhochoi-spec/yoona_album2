# 윤아 사진첩 2

사진을 콕 누르면 할머니 목소리와 자막이 나오는 윤아 사진첩입니다. (2024~2026년 사진 32장, 할머니 녹음 32개)

## 폴더 구성
- `index.html` : 사진첩 화면 (연도 탭 2024 · 2025 · 2026)
- `photos/p001.jpg ~ p032.jpg` : 사진
- `voices/p001.mp3 ~ p032.mp3` : 할머니 목소리 (파일 번호 = 사진 번호)
- `data/voices.json` : 사진 번호와 목소리 파일 연결표
- `.nojekyll` : GitHub Pages가 파일을 그대로 올리도록 하는 빈 파일 (지우지 마세요)

## GitHub Pages로 올리는 순서
1. GitHub에서 **New repository** → 이름 예: `yoona-album2` → **Public** 선택 → Create
2. **Add file → Upload files** → 이 폴더 안의 모든 파일과 폴더(index.html, photos, voices, data, .nojekyll, README.md)를 끌어다 놓고 **Commit changes**
   - `.nojekyll`이 숨김 파일이라 안 보이면 없어도 동작합니다.
3. **Settings → Pages → Branch: main / (root) → Save**
4. 1~2분 뒤 `https://<GitHub아이디>.github.io/yoona-album2/` 주소로 열립니다. 이 주소를 가족에게 보내면 됩니다.

## 참고
- 휴대폰 첫 화면에 추가하면 앱처럼 쓸 수 있습니다 (사파리/크롬 → 공유 → 홈 화면에 추가).
- 저장소를 Public으로 하면 주소를 아는 사람은 누구나 사진을 볼 수 있습니다.
