````markdown
# MSA 기반 SurveyPulse Eureka 서버

SurveyPulse 플랫폼의 마이크로서비스 디스커버리를 담당하는 Eureka 서버입니다. 각 서비스가 본 서버에 등록되어 동적 라우팅 및 부하 분산에 활용됩니다.

## 주요 기능

- **서비스 등록 (Service Registration)**
  - User, Survey, Response, Report, Advertise, Gateway 서비스가 Eureka에 등록
- **서비스 조회 (Service Discovery)**
  - 각 마이크로서비스에서 Eureka 클라이언트로 다른 서비스 인스턴스 조회
- **대시보드**
  - 웹 UI를 통해 등록된 인스턴스 목록과 상태 확인

## 기술 스펙

- **언어 & 프레임워크**: Java, Spring Boot
- **서비스 디스커버리**: Spring Cloud Netflix Eureka Server

