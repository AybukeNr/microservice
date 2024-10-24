#çalıştıracağımız jdk
FROM amazoncorretto:21.0.2-alpine3.19

#uygulamanın jar dosyasının bulunduğu yer,docker imajı kök dizine accounts.jar adıyla kopyalanacak
COPY build/libs/accounts-v0.1.jar accounts.jar

#jar'ı çalıştır
ENTRYPOINT ["java","-jar","/accounts.jar"]
