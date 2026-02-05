FROM eclipse-temurin:25-jre-alpine

RUN addgroup -S spring && adduser -S spring -G spring
USER spring

WORKDIR /opt/app

COPY --chown=spring:spring japp.jar /opt/app/japp.jar

ENTRYPOINT ["java", "-XX:+UseContainerSupport", "-XX:MaxRAMPercentage=75.0", "-jar", "/opt/app/japp.jar"]
