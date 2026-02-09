# 🖼️ 육산갈비 실제 매장 이미지 적용 완료!

## ✨ 적용된 실제 이미지

### 슬라이드 1: 매장 전경 (slide1.jpg)
- **원본**: 매장이미지4.jpeg
- **내용**: 세종시 220평 프리미엄 매장 전경
- **특징**: 넓은 테이블, 고급스러운 덕트 시스템, 모던한 인테리어
- **메시지**: "산(山)처럼 우직한 고기(肉) 철학 육산"

### 슬라이드 2: 양념 갈비 (slide2.jpg)
- **원본**: 육산이미지1.jpeg
- **내용**: 30년 비법 양념갈비와 반찬들
- **특징**: 정갈한 한식 상차림, 고품질 양념육
- **메시지**: "8년 연속 월 2~3억 매출, 검증된 수익력"

### 슬라이드 3: 매장 내부 (slide3.jpg)
- **원본**: 매장이미지1.jpeg
- **내용**: 고급스러운 매장 내부 인테리어
- **특징**: 벽돌 벽, 꽃 장식, 프리미엄 분위기
- **메시지**: "50평 이상 대형 매장 최적화 시스템"

### 슬라이드 4: 냉면 (slide4.jpg)
- **원본**: 냉면2.jpeg
- **내용**: 자가제면 수제 냉면
- **특징**: 시원한 비주얼, 고급 그릇, 정갈한 플레이팅
- **메시지**: "점심·저녁 풀타임 빈틈없는 매출 구조"

---

## 📁 폴더 구조

```
yuksan-website/
├── index.html (메인 페이지)
└── images/
    ├── slide1.jpg (매장 전경)
    ├── slide2.jpg (양념 갈비)
    ├── slide3.jpg (매장 내부)
    ├── slide4.jpg (냉면)
    └── ... (추가 이미지들)
```

---

## 🚀 배포 방법

### 방법 1: Netlify Drop (가장 쉬움!)

1. **https://app.netlify.com/drop** 접속
2. **`yuksan-website` 폴더 전체**를 드래그 앤 드롭
3. 즉시 URL 생성! (예: https://yuksan-galbi.netlify.app)

### 방법 2: GitHub Pages

1. GitHub 저장소 생성
2. `yuksan-website` 폴더 내용 업로드
3. Settings → Pages → 활성화
4. URL: https://yourname.github.io/yuksan

### 방법 3: 직접 호스팅 (Cafe24, Hosting Korea 등)

1. FTP 접속
2. `index.html`과 `images` 폴더 업로드
3. 도메인 연결 (www.yuksan.com)

---

## 🎨 이미지 최적화 완료

### 파일 크기
- slide1.jpg: 301KB (최적화됨)
- slide2.jpg: 333KB (최적화됨)
- slide3.jpg: 140KB (최적화됨)
- slide4.jpg: 128KB (최적화됨)

### 로딩 속도
- ✅ 웹 최적화 완료
- ✅ 빠른 로딩 보장
- ✅ 모바일 친화적

---

## 💡 CodePen 업로드 방법

CodePen은 외부 이미지 링크가 필요합니다.

### 옵션 A: 이미지 호스팅 후 사용

1. **Imgur.com**에 이미지 업로드
   - https://imgur.com/upload
   - 4개 이미지 업로드
   - 각 이미지 링크 복사

2. **CodePen HTML 수정**
   ```html
   <!-- Slide 1 -->
   <div class="hero-background" style="background-image: url('https://i.imgur.com/xxxxx.jpg');"></div>
   ```

### 옵션 B: Base64 인라인 (파일 크기 증가)

이미지를 Base64로 변환하여 직접 삽입 (비추천 - 파일 크기 큼)

---

## 📸 추가 이미지 활용 제안

업로드된 다른 이미지들:
- `다운로드.jpeg` - 테이블 세팅
- `다운로드__1_.jpeg` - 매장 외관
- `다운로드__3_.jpeg` - 입구
- `매장이미지3.jpeg` - 전체 뷰
- `육산이미지2.jpeg` - 음식 클로즈업

### 활용 방안
1. **갤러리 섹션** 추가
2. **메뉴 섹션**에 음식 이미지 추가
3. **스토리 카드**에 매장 사진 배경
4. **Footer**에 작은 갤러리

---

## 🎯 슬라이더 작동 확인

### 테스트 체크리스트
- [ ] 4개 슬라이드 모두 이미지 표시
- [ ] 자동 전환 (5초)
- [ ] 좌우 화살표 작동
- [ ] Dots 클릭 작동
- [ ] 키보드 방향키 작동
- [ ] 마우스 호버 일시정지
- [ ] Ken Burns 줌 효과
- [ ] 모바일 반응형

---

## 🌐 실제 배포 예시

### Netlify 배포 시
```
Your site is live at:
https://yuksan-galbi.netlify.app

- 모든 이미지 자동 로드
- HTTPS 자동 적용
- 글로벌 CDN 배포
```

### GitHub Pages 배포 시
```
Your site is published at:
https://yourname.github.io/yuksan/

- 무료 호스팅
- 커스텀 도메인 연결 가능
- 자동 HTTPS
```

---

## 🔧 이미지 교체 방법

나중에 다른 매장 사진으로 변경하려면:

1. `images` 폴더에 새 이미지 추가
2. 파일명을 `slide1.jpg`, `slide2.jpg` 등으로 교체
3. 또는 `index.html`에서 경로 수정:
   ```html
   <div class="hero-background" style="background-image: url('images/새이미지.jpg');"></div>
   ```

---

## 📞 문의

**육산갈비**
- 📱 전화: 010-6601-2927
- 📧 이메일: ys-food@naver.com
- 🌐 도메인: www.yuksan.com (예정)

---

## 🎉 완성!

**실제 육산갈비 매장 사진**으로 메인 비주얼 슬라이더 완성!

- ✅ 4개 슬라이드 롤링
- ✅ 실제 매장 이미지
- ✅ 고품질 사진
- ✅ 빠른 로딩
- ✅ 배포 준비 완료

**지금 바로 Netlify Drop으로 배포하세요!** 🚀

---

<div align="center">

**Made with ❤️ for Yuksan Galbi**

[⬆ 맨 위로](#육산갈비-실제-매장-이미지-적용-완료)

</div>
