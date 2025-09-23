# Stadium Backend

##  프로젝트 소개
**Stadiumly**는 야구 직관러를 위한 앱으로,  
**각 구장별 선발투수 정보, 날씨에 의한 우천취소 여부, 각 구단별 선수들의 추천맛집** 등  
야구장 직관경험을 바탕으로 야구장을 방문하려는 사람들에게 필요한 기능을 제공합니다.  

---

## ✨ 핵심 기능
- 🔐 **사용자 인증** : 회원가입, 로그인, JWT 기반 토큰 인증  
- 🏪 **스토어 API** : 구장내의 먹거리 정보
- ⚡ **데이터 파이프라인** : KBO 데이터 크롤링 → 정제 → DB 저장 자동화  

---

## 🛠 기술 스택
### Backend
- **NestJS (Node.js)**
- **Prisma ORM**
- **PostgreSQL 
- **Redis (캐싱)**

### Infra & DevOps
- **Docker / Docker Compose**
- **Azure Blob Storage**
- **Scheduler (Cron Job)**

