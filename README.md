# dev-error-log
# 개발 에러 & 오답 노트

Java / Spring / SQL 공부 중
직접 겪은 에러와 해결 과정을 기록한 저장소입니다.

## 기록 목적
- 같은 실수를 반복하지 않기
- 문제 해결 과정을 설명할 수 있게 정리
- 전산직 면접 대비

## 작성 규칙
- 에러 1개 = 기록 1개
- 복붙 ❌ / 직접 겪은 것만 기록

26-01-18
# status=404 에러
# 원인
build.gradle 의존성 누락
# 해결방법
implementation 'org.springframework.boot:spring-boot-starter-thymeleaf’ 의존성 추가 
# 배운 점
프로젝트 시작시 의존성의 중요성 확인
