# GitHub Pages 배포 방법

이 폴더(`dist`) 안의 파일만 GitHub 저장소에 올리면 됩니다.

## 처음 올릴 때

1. GitHub에서 새 저장소를 만듭니다.
   - 예: `home-safety-game`
   - Public 저장소로 만들면 GitHub Pages 사용이 쉽습니다.
2. 이 `dist` 폴더 안의 모든 파일과 폴더를 저장소에 업로드합니다.
   - `index.html`
   - `.nojekyll`
   - `profile_images`
   - `scene_images_v3`
   - 나머지 `.webp`, `.svg` 파일
3. GitHub 저장소에서 `Settings` → `Pages`로 이동합니다.
4. `Build and deployment`에서 아래처럼 설정합니다.
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`
5. 저장 후 1~3분 정도 기다리면 주소가 생깁니다.

## 접속 주소 형식

보통 아래 형식입니다.

```text
https://깃허브아이디.github.io/저장소이름/
```

예:

```text
https://yourname.github.io/home-safety-game/
```

이 주소를 인스타그램 프로필, 게시물 설명, QR 코드에 넣으면 됩니다.

## 수정 후 다시 올릴 때

웹 내용을 수정한 뒤에는 이 `dist` 폴더를 다시 만들거나, 바뀐 파일만 GitHub 저장소에 덮어올리면 됩니다.

