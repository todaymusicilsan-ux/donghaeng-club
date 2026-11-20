# 동행클럽 (DONGHAENG CLUB)

> **읽고, 쓰고, 나누며 삶의 반경을 넓히는 곳**  
> 트레바리 스타일의 취향과 대화 중심 프리미엄 커뮤니티 & 프로그램 서비스

---

## 🌟 주요 기능
- **브랜드 히어로 & 철학**: 3가지 원칙 (독후감 의무제, 검증된 호스트, 안전한 살롱)
- **클럽/프로그램 탐색 & 필터**: 인문·철학, 커리어·비즈니스, 와인·미식, 창작·글쓰기 카테고리 필터 및 실시간 검색
- **클럽 상세 팝업**: 4회차 커리큘럼, 선정 도서, 호스트 소개, 일정/장소
- **멤버십 신청 시스템**: 원클릭 신청 폼 및 `/api/apply` 접수 처리
- **멤버 생생 후기 & FAQ 아코디언**
- **반응형 웹 디자인**: 모바일, 태블릿, PC 완벽 대응

---

## 🚀 로컬 실행 방법

```bash
# 서버 실행 (Node.js 기본 모듈로 별도 설치 불필요)
node server.js
```

브라우저에서 `http://localhost:3000` 접속

---

## ☁️ Railway 배포 가이드

1. **GitHub 리포지토리 푸시**:
   ```bash
   git add .
   git commit -m "feat: initial commit for Donghaeng Club"
   git push -u origin main
   ```
2. **Railway 연결**:
   - [railway.com](https://railway.com) 접속
   - GitHub 계정으로 로그인 (`todaymusicilsan-ux`)
   - **New Project** &rarr; **Deploy from GitHub repo** &rarr; `donghaeng-club` 선택
   - Railway가 `server.js`를 자동 감지하여 1분 이내에 무료 HTTPS 배포 완료!
