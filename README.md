Bu projede; Titanik gemisindeki yolcuların, çeşitli koşullar ele alınarak, yaşanan felaketten sağ çıkma durumu tahmin edilmektedir.
Kaggle’dan elde edilen csv formatındaki train.csv veri setinde yolcu kayıtları ve yolculara ait bilgiler yer almaktadır. Bu bilgiler ön işlemeden geçirildikten sonra model eğitilmiştir. Model %80 doğrulukla çalışmıştır.
Daha sonra test.csv veri setindeki bilgiler satır satır akış halinde modele gönderilerek tahmin sonuçlarının da yine akış halinde alınması Apache Kafka ve Apache Streaming ile sağlanmıştır.
