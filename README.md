# FolderDrive OAuth 소개 사이트

외부에 아직 게시하지 않은 정적 웹사이트 파일입니다. 현재 앱 코드의 동작을 기준으로 작성한 소개와 개인정보처리방침이며, 공개 전에 운영자 이름·문의 이메일·시행일·실제 운영 방식을 확인하세요. 사이트 공개만으로 Google의 브랜딩/범위 검증이나 OAuth 게시 승인을 보장하지 않습니다.

## 무료 GitHub Pages 공개

1. ZIP을 풀고 GitHub에 `folderdrive-site`라는 새 공개(Public) 저장소를 만듭니다. 공개할 소개 페이지용 저장소입니다.
2. 저장소에서 Add file → Upload files로 `index.html`, `privacy.html`, `style.css`, `icon.png`, `.nojekyll`을 저장소 최상위에 올리고 Commit changes를 누릅니다. 폴더나 ZIP 자체를 업로드하지 마세요.
3. Settings → Pages → Build and deployment에서 Source를 Deploy from a branch, Branch를 main, 폴더를 /(root)로 정하고 Save를 누릅니다.
4. 배포 완료 후 Pages에 표시되는 실제 사이트 주소를 엽니다. 시크릿 창에서도 두 페이지가 로그인 없이 열리는지 확인하세요.
5. Google Cloud의 새 FolderDrive 프로젝트 → Google 인증 플랫폼 → 브랜딩에서 아래 두 주소를 입력하고 저장합니다.

GitHub 계정이 `pjm9824`이고 위 저장소 이름을 사용한 경우 예상 주소는 다음과 같습니다. **Pages 배포 후 실제로 열리는 것을 확인하기 전에는 사용하지 마세요.**

- 홈페이지: `https://pjm9824.github.io/folderdrive-site/`
- 개인정보처리방침: `https://pjm9824.github.io/folderdrive-site/privacy.html`
- 승인된 도메인을 요구하는 경우: `pjm9824.github.io` (https://와 경로 제외)

로고와 서비스 약관은 추가하지 않은 상태로 진행하고 콘솔이 표시하는 요구사항을 확인하세요. 도메인 소유권 확인을 요구하면 Google Search Console에서 실제 Pages 주소의 URL 접두어 속성을 등록한 뒤 HTML 확인 파일을 같은 저장소 최상위에 추가하여 확인할 수 있습니다. Google이 상위 도메인 소유권을 요구하거나 해당 호스팅 도메인을 허용하지 않는 경우에는 소유권을 확인할 수 있는 다른 호스팅/도메인이 필요합니다.

브랜딩 저장 후 대상 → 앱 게시를 다시 확인하세요. 계속 비활성화되어 있다면 콘솔의 구체적인 누락 안내를 확인해야 합니다. 이번 파일은 웹 공개 준비물이므로 APK나 OAuth 클라이언트를 변경하지 않습니다.
