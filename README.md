# 로마서8장 암송 앱 (PWA)

## 파일
- index.html : 앱 본체
- config.js : Supabase 연결 정보 (URL, anon key)
- manifest.webmanifest, sw.js, icon-*.png : 앱 설치(PWA)용

## 설치 가능하게 올리기 (https 필수)
1. 이 폴더를 git 레포지토리에 커밋합니다.
2. GitHub Pages / Netlify / Vercel / Cloudflare Pages 중 하나로 호스팅합니다. (모두 무료, https 자동)
3. 휴대폰에서 그 주소를 엽니다.
   - 안드로이드(크롬): 주소창 메뉴 → "앱 설치" 또는 앱 안의 [📲 앱 설치] 버튼
   - 아이폰(사파리): 공유 버튼 → "홈 화면에 추가"
4. config.js에 Supabase URL / anon key를 넣거나, 앱에서 처음 한 번 입력합니다.

## 참고
- 마이크 녹음, 소리 듣기 등은 https 주소에서 가장 잘 동작합니다.
