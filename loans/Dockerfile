#çalıştıracağımız jdk
FROM amazoncorretto:21.0.2-alpine3.19

#uygulamanın jar dosyasının bulunduğu yer,docker imajı kök dizine accounts.jar adıyla kopyalanacak
COPY build/libs/loans-v0.1.jar loans.jar

#jar'ı çalıştır
ENTRYPOINT ["java","-jar","/loans.jar"]
