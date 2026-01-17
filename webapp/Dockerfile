FROM debian:trixie-slim

# Install Java 25
RUN apt-get update
RUN apt-get install -y --no-install-recommends openjdk-25-jdk
RUN rm -rf /var/lib/apt/lists/*


# Set JAVA_HOME
ENV JAVA_HOME=/usr/lib/jvm/java-25-openjdk
ENV PATH="$JAVA_HOME/bin:$PATH"

WORKDIR /app
COPY . /app

# Expose your web server port (example: 8080)
EXPOSE 8080

# Run your Java app
CMD sh -c 'java -jar *.jar'

