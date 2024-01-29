# Araç Kiralama Sistemi

Bu proje, kullanıcıların araç kiralayabileceği bir sistem üzerinde çalışmaktadır. Proje Java dilinde yazılmıştır.

## Kullanım

Kullanıcılar sisteme giriş yapabilir ve araç kiralayabilirler. Kiralama bilgileri veritabanında saklanır.

## Yapı

Proje aşağıdaki ana paketlere ayrılmıştır:

- `business`: İş mantığı sınıflarını içerir.
- `core`: Çekirdek işlevsellikleri içerir.
- `dao`: Veritabanı erişim nesnelerini içerir.
- `entity`: Veritabanı tablolarını temsil eden sınıfları içerir.
- `view`: Kullanıcı arayüzünü içerir.

1. `App`: Bu sınıf, uygulamanın ana giriş noktasıdır. `main` metodu içerir ve uygulamanın başlatılmasını sağlar.

2. `LoginView`: Bu sınıf, kullanıcıların sisteme giriş yapmalarını sağlayan kullanıcı arayüzünü temsil eder.

3. `BookingView`: Bu sınıf, kullanıcıların araç rezervasyonu yapmalarını sağlayan kullanıcı arayüzünü temsil eder.

4. `BookManager`: Bu sınıf, rezervasyon işlemlerini yönetir. Rezervasyonların kaydedilmesi, silinmesi ve alınması gibi işlemleri içerir.

5. `BookDao`: Bu sınıf, veritabanı ile rezervasyonlar arasındaki etkileşimi yönetir. Rezervasyonların veritabanına kaydedilmesi, silinmesi ve alınması gibi işlemleri içerir.

6. `Book`: Bu sınıf, bir rezervasyonu temsil eder. Rezervasyonun özelliklerini (örneğin, rezervasyon yapan kişi, rezervasyon tarihleri, rezervasyonun durumu vb.) saklar.
