FROM openjdk:25-slim


WORKDIR /app

# Expose your web server port to allow for LAN connections
#EXPOSE 8080

# allow volume for updated JAR
VOLUME ["/app"]

# Run your Java app
CMD sh -c 'java -jar *.jar'

