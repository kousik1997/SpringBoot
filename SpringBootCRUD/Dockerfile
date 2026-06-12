FROM azul/zulu-openjdk:17
 
WORKDIR /app
 
COPY target/SpringBootCRUD.jar app.jar
 
EXPOSE 9090
 
ENTRYPOINT ["java","-jar","app.jar"]