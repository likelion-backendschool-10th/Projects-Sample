##  설치 및 실행

### 1. 프로젝트 다운로드

```bash
git clone [GitHub Repository URL]
cd [Project Directory]
```

### 2. Backend 설정

Backend 디렉터리로 이동합니다.

```bash
cd backend
```

**Maven Wrapper를 사용하는 경우 (권장)**

Linux / macOS:
```bash
./mvnw spring-boot:run
```

Windows:
```bash
mvnw.cmd spring-boot:run
```

**Maven이 별도로 설치된 경우**

```bash
mvn spring-boot:run
```

### 3. Frontend 설정

Frontend 디렉터리로 이동하여 필요한 패키지를 설치하고 개발 서버를 실행합니다.

```bash
cd frontend
npm install
npm run dev
```

### 4. Docker Compose 실행

프로젝트 루트 디렉터리에서 실행합니다.

**컨테이너 빌드 및 실행**

```bash
docker compose up -d --build
```

**컨테이너 실행 상태 확인**

```bash
docker compose ps
```

**컨테이너 로그 확인**

```bash
docker compose logs -f
```

**컨테이너 종료**

```bash
docker compose down
```

---

## 🔧 환경 변수 설정

각 컴포넌트별 환경 변수를 설정합니다.

### Backend (.env)

```ini
SPRING_DATASOURCE_URL=jdbc:mysql://localhost:3306/[DATABASE_NAME]
SPRING_DATASOURCE_USERNAME=[DB_USERNAME]
SPRING_DATASOURCE_PASSWORD=[DB_PASSWORD]
```

### Frontend (.env)

```ini
VITE_API_URL=http://localhost:8080
```

※ 실제 API 주소 및 환경 변수 이름은 프로젝트 설정에 맞게 변경합니다.

※ Spring Boot에서 `.env` 파일을 사용하려면 별도의 환경 변수 로딩 설정이 필요할 수 있습니다.

---

##  API 문서

Spring Boot 기반 API 문서를 제공하는 경우 다음 주소를 통해 확인할 수 있습니다.

- **Backend API:** `http://localhost:8080`
- **Swagger UI:** `http://localhost:8080/swagger-ui/index.html`
- **OpenAPI JSON:** `http://localhost:8080/v3/api-docs`

※ Swagger 및 OpenAPI는 `springdoc-openapi` 등의 관련 라이브러리와 설정이 적용된 경우 사용할 수 있습니다.

---

##  테스트

### Backend 테스트

Maven 기반 테스트를 실행합니다.

Linux / macOS:

```bash
cd backend
./mvnw test
```

Windows:

```bash
cd backend
mvnw.cmd test
```

Maven이 별도로 설치된 경우:

```bash
mvn test
```

**테스트 및 빌드 실행**

```bash
./mvnw clean package
```

Windows:

```bash
mvnw.cmd clean package
```

### Frontend 테스트

```bash
cd frontend
npm test
```

※ Frontend 테스트 스크립트가 `package.json`에 등록된 경우 실행할 수 있습니다.

---

##  모니터링 및 운영

- **AWS CloudWatch**: 서버 및 애플리케이션 로그와 모니터링
- **NGINX**: 리버스 프록시 및 포트 스위칭 방식 무중단 배포
- **Docker**: 컨테이너 실행 상태 및 로그 확인
- **GitHub Actions**: CI/CD 자동화
- **Maven**: Backend 의존성 관리 및 빌드 자동화

### Docker 로그 확인

```bash
docker compose logs -f
```

### 배포 환경 확인

- AWS EC2 서버 접속 및 상태 확인
- NGINX 프록시 연결 상태 확인
- GitHub Actions 배포 워크플로우 실행 결과 확인
- CloudWatch 로그 및 모니터링 지표 확인
- Docker 컨테이너 실행 상태 및 로그 확인

---

##  참고 사항

- Backend는 Java 및 Maven 기반 Spring Boot 프로젝트를 기준으로 작성되었습니다.
- Maven Wrapper(`mvnw`, `mvnw.cmd`)가 프로젝트에 포함되어 있다면 별도의 Maven 설치 없이 빌드 및 실행할 수 있습니다.
- Frontend는 Node.js 및 npm 기반 프로젝트를 기준으로 작성되었습니다.
- Docker Compose를 사용하려면 Docker Desktop 또는 Docker Engine이 설치되어 있어야 합니다.
- 실제 실행 명령어와 포트 번호는 프로젝트의 설정에 따라 달라질 수 있습니다.

