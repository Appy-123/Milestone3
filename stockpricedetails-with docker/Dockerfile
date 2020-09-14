FROM openjdk:8
EXPOSE 8190
ADD target/stockprice.jar stockprice.jar
ENTRYPOINT ["java", "-jar", "stockprice.jar"]
