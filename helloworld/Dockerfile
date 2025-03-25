# Sử dụng base image OpenJDK
FROM openjdk:17-jdk-slim

# Sao chép file JAR của ứng dụng Spring Boot vào container
COPY target/*.jar app.jar

# Mở cổng mà ứng dụng Spring Boot chạy (thường là 8080)
EXPOSE 8080

# Lệnh chạy ứng dụng Spring Boot
ENTRYPOINT ["java", "-jar", "app.jar"]