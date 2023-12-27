# 베이스 이미지 선택 (Java 17을 사용)
FROM openjdk:17-jdk

# 작업 디렉토리 설정
WORKDIR /app

# Maven 패키지 및 의존성을 복사
COPY target/dependency/ . 

# 어플리케이션 JAR 파일 복사
COPY target/user-service-0.0.1-SNAPSHOT.jar app.jar

# 앱 실행 명령
CMD ["java", "-jar", "app.jar"]
