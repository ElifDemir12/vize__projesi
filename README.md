Sinema Bilet Sistemi
Bu proje, Java ile geliştirilmiş basit bir sinema bilet yönetim sistemidir. Salonlar, müşteriler ve filmlerle ilgili temel işlemleri gerçekleştirir.

Özellikler
Film Yönetimi: Her salon için film adı, süresi ve türü gibi bilgiler tutulur.
Müşteri Yönetimi: Müşteriler ID, isim ve e-posta bilgileriyle sisteme kaydedilir, salonlara atanabilir.
Salon Yönetimi: Salonlar ID ve ad bilgisiyle oluşturulur; atanan film ve kayıtlı müşteriler listelenebilir.
Kullanıcı Arayüzü: Metin tabanlı menü ile sorgulama ve görüntüleme işlemleri yapılır.

Teknik Yapı
Abstract Class: BaseEntity, Musteri ve Salon sınıflarına temel özellikler sağlar.
Interface: IBiletSistemi, sistemin temel işlevlerini tanımlar.
Inheritance: Musteri ve Salon sınıfları BaseEntity’den türetilmiştir.
Polymorphism: BilgiGoster() metodu her sınıf için farklı davranır.






