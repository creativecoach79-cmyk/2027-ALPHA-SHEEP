# 트렌드 코리아 2027 — ALPHA SHEEP / HR Insight

10개 소비트렌드의 개념, HR 해석, 실행 전략과 해설 영상을 담은 정적 웹사이트입니다.

## GitHub Pages 배포

1. ZIP을 압축 해제합니다. ZIP 자체를 저장소에 업로드하지 않습니다.
2. `index.html`, CSS·JS 파일, `keywords`, `media`, 이미지와 `.github` 폴더를 저장소 루트에 복사합니다.
3. GitHub 저장소의 Settings → Pages → Source에서 **GitHub Actions**를 선택합니다.
4. 기본 브랜치가 `main`이면 push 후 자동 배포됩니다. 다른 브랜치라면 `.github/workflows/pages.yml`의 브랜치를 수정합니다.
5. Actions의 Deploy website to GitHub Pages 워크플로에서 배포 결과와 URL을 확인합니다.

영상이 포함되어 있으므로 웹 업로드보다 GitHub Desktop 또는 로컬 Git clone에서 파일을 복사하고 commit/push하는 방식이 편리합니다. `.github` 폴더도 반드시 포함합니다.

상대 경로를 사용하므로 저장소 하위 경로의 GitHub Pages에서도 이용할 수 있습니다.
