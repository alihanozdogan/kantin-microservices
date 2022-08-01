# Kod
Identity Api içerisinde role based authentication yapılması gerekiyor onun haricinde gördüğüm bir eksik kalmamıştır.
kantin-microservices-main\src\Services dizini altındaki apilar örnek oluşturması içindir. Bu apiların silinip yerine proje ekiplerinden alınan apiların yerleştirilmesi ve Apı gatewayde konumlarının verilmesi gerekmektedir. Ayrıca Customer Api dockerfile eklenmesi gerekmektedir. Docker-compose dosyasının düzenlenmesi ve yeni eklenen apilara göre gerekiyorsa port ataması ve path düzenlenmesi yapılacaktır.
# API Gateway
kantin-microservices-main\src\ApiGateways\Envoy\config dizini altında bulunan config dosyaları projemize eklenen apiların pathlerine göre düzenlenmeli
Mobil uygulama için herhangi bir şey yapılmadı.

# Kaynak 
Yardım alabileceğiniz en iyi kod aşağıdadır.
https://github.com/dotnet-architecture/eShopOnContainers
* [Kod](https://github.com/dotnet-architecture/eShopOnContainers)
* [Kaynakça](https://docs.microsoft.com/tr-tr/dotnet/architecture/cloud-native/introduce-eshoponcontainers-reference-app)
