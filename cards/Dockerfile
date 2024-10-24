#çalıştıracağımız jdk
FROM amazoncorretto:21.0.2-alpine3.19

#uygulamanın jar dosyasının bulunduğu yer,docker imajı kök dizine accounts.jar adıyla kopyalanacak
COPY build/libs/cards-v0.1.jar cards.jar

#jar'ı çalıştır
ENTRYPOINT ["java","-jar","/cards.jar"]
