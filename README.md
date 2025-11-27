# 🔐 yml_jasypt

Spring Boot 환경에서 **Jasypt를 이용한 application.yml 암호화** 예제 프로젝트입니다.

## 🔧 주요 기능
- yml 설정 파일 내 DB 비밀번호 / API Key 암호화
- `ENC()` 형식으로 설정값 보호
- 환경변수 또는 JVM 옵션으로 복호화 키 주입

## 💡 사용 기술
- Spring Boot 3.x  
- Java 17+  
- jasypt-spring-boot-starter

## 🚀 실행 방법
```bash
java -Djasypt.encryptor.password=비밀키 -jar 프로젝트.jar
