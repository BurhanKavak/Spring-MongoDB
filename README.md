# :triangular_flag_on_post: NoSQL -> MongoDB
![](images/mongodb.png)
## 🎯 NoSQL nedir?
<b>
NoSQL, "Not Only SQL" olarak da bilinen bir veritabanı türüdür. İlişkisel veritabanlarına alternatif olarak ortaya çıkmıştır ve daha ölçeklenebilir, daha esnek ve daha hızlı veri saklama ve yönetme özellikleri sunar.</b>

<b> İlişkisel veritabanları, verileri tablolar halinde tutarlar ve bu tablolar arasında ilişki kurarlar. Bu veritabanları genellikle SQL (Structured Query Language) adlı bir sorgu dili kullanılarak yönetilirler. İlişkisel veritabanları, özellikle işletme ve kurumsal uygulamalar için yaygın olarak kullanılır.<br></b>

<b> NoSQL veritabanları, verileri tablolar yerine anahtar-değer, sütun tabanlı veya belge tabanlı şekilde saklarlar. NoSQL veritabanları daha esnek bir veri yapısına sahip oldukları için, ilişkisel veritabanlarına göre daha kolay ölçeklenebilirler ve daha fazla veri tipi ile çalışabilirler. NoSQL veritabanları için genellikle SQL dışındaki sorgu dilleri kullanılır.</b>


## 🎯 MongoDB nedir?

<b>MongoDB, NoSQL veritabanlarından biridir ve belge tabanlı bir veritabanıdır. Veriler, BSON (Binary JSON) formatında belgeler şeklinde saklanır. MongoDB, özellikle büyük ve dağıtık sistemler için iyi bir seçimdir. Ayrıca, MongoDB, yüksek performans ve ölçeklenebilirlik sunar. MongoDB, JSON veri formatına benzer bir sorgu dili olan MongoDB Query Language (MQL) kullanarak yönetilir.

İlişkisel veritabanları ve NoSQL veritabanları arasındaki farklar, veri saklama ve yönetme yaklaşımları, veri yapısı ve sorgu dilleri gibi birkaç farklı alanda bulunur. İlişkisel veritabanları daha yapılandırılmış ve sıkı bir veri yapısına sahiptir, ancak NoSQL veritabanları daha esnek bir veri yapısına sahiptir ve daha fazla veri türü ile çalışabilirler. İlişkisel veritabanları genellikle SQL sorgu dili kullanırlar, ancak NoSQL veritabanları için SQL dışındaki sorgu dilleri kullanılır.</b>


## :pushpin: MongoDB bağımlılığı :

```xml
<dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-data-mongodb</artifactId> 
</dependency>
```

## :pushpin: MongoDB docker compose yaml dosyası :

```yaml
version: '20.10.17'
services:
  mongo:
    image: mongo
    ports:
      - '27017:27017'
    command: --serviceExecutor adaptive
```

