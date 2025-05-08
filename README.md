# POPDCU Deploy

대동제 클릭 게임 POPDCU의 배포 설정 프로젝트입니다.

## 구성 요소

- **PostgreSQL**: 데이터베이스 서버
- **pgAdmin**: 데이터베이스 관리 도구
- **Backend**: Spring Boot 백엔드 서버
- **Frontend**: Vue.js 프론트엔드 서버 (Nginx로 제공)

## 실행 방법

Docker와 Docker Compose가 설치되어 있어야 합니다.

```bash
# 모든 서비스 실행
docker-compose up -d

# 서비스 상태 확인
docker-compose ps

# 로그 확인
docker-compose logs -f

# 모든 서비스 중지
docker-compose down
```

## 접속 방법

- **프론트엔드**: http://localhost
- **백엔드 API**: http://localhost:8080/api
- **pgAdmin**: http://localhost:5051 (Email: admin@admin.com, Password: admin)
- **PostgreSQL**: localhost:5433 (User: admin, Password: admin, Database: popdcu_db)
