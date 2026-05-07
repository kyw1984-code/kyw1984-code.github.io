# Shocktree Legal Pages

Privacy Policy + Terms of Service pages for all 4 apps. Hosted on GitHub Pages.

## URLs (after deployment)

```
https://shocktree-hoonpro.github.io/legal/
https://shocktree-hoonpro.github.io/legal/focusfox/privacy.html
https://shocktree-hoonpro.github.io/legal/focusfox/terms.html
https://shocktree-hoonpro.github.io/legal/snapshelf/privacy.html
https://shocktree-hoonpro.github.io/legal/snapshelf/terms.html
https://shocktree-hoonpro.github.io/legal/receiptvault/privacy.html
https://shocktree-hoonpro.github.io/legal/receiptvault/terms.html
https://shocktree-hoonpro.github.io/legal/stylematch/privacy.html
https://shocktree-hoonpro.github.io/legal/stylematch/terms.html
```

## Deployment (최초 1회)

1. GitHub Org `shocktree-hoonpro`에 `legal` 레포 생성 (Public)
2. 이 `legal/` 폴더 내용을 레포 루트에 push:
   ```bash
   cd legal/
   git init
   git add .
   git commit -m "chore: initial legal pages"
   git remote add origin git@github.com:shocktree-hoonpro/legal.git
   git push -u origin main
   ```
3. GitHub Repo Settings → Pages → Source: `main` branch, `/` (root) → Save
4. Enforce HTTPS 체크 확인

## Store Listing에 등록할 URL

**App Store Connect** (앱 정보 → 마케팅 URL / Support URL):

```
https://shocktree-hoonpro.github.io/legal/focusfox/privacy.html
https://shocktree-hoonpro.github.io/legal/snapshelf/privacy.html
https://shocktree-hoonpro.github.io/legal/receiptvault/privacy.html
https://shocktree-hoonpro.github.io/legal/stylematch/privacy.html
```

**Google Play Console** (스토어 정보 → 개인정보처리방침 URL):
위와 동일

## 업데이트 방법

정책 변경 시 해당 HTML 파일 수정 후 `legal` 레포에 commit + push.  
`updated` 날짜를 반드시 갱신할 것.

## ⚠️ 법적 고지

이 파일들은 **템플릿** 수준입니다. 실제 출시 전, 특히 ReceiptVault(세금/재무 면책 문구)는 변호사 검토를 받으세요.
