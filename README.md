Bu repo, Murat Yücedağ'ın C# Eğitim Kampı boyunca adım adım ilerleyerek geliştirdiğim projeleri içermektedir. C# öğrenme sürecimde temel konuları sağlamlaştırmak, programlama mantığını kavramak ve uygulama geliştirme becerilerimi güçlendirmek amacıyla çeşitli projeler tamamladım. Her bir proje, teorik bilgiyi pratiğe dönüştürerek deneyim kazanmama yardımcı oldu.

Aşağıda, kamp boyunca üzerinde çalıştığım projelerin detayları ve bu süreçte edindiğim teknik yetkinlikler yer almaktadır:

🚀 Proje 1: Merhaba Dünya!

Bu başlangıç projesinde, .NET çalışma mantığını ve bir C# konsol uygulamasının giriş noktası olan Main metodunu inceledim. Console.WriteLine() ile temel çıktı işlemlerini gerçekleştirerek program akışının nasıl başlatıldığını öğrendim.

🔢 Proje 2: Değişkenler

Bu projede C# dilindeki temel veri türlerini (int, string, double, bool vb.) ve bellek üzerinde nasıl temsil edildiklerini öğrendim. Tür dönüşümleri, aritmetik işlemler ve değişken yaşam döngüsü gibi konuları test ederek temel programlama mantığımı geliştirdim.

🧩 Proje 3: Diziler (Arrays)

Statik veri yapıları olan diziler üzerinde çalışarak birden fazla değeri aynı veri türünde tek bir koleksiyonda tutmayı öğrendim. Döngülerle dizi elemanlarına erişme, dizi uzunluğu kontrolü ve temel algoritmalar üzerinde pratik yaptım.

⚖️ Proje 4: Karar Yapıları (If-Else)

Koşullu ifadeler ile programın akışını kontrol etmeyi öğrendim.
if / else if / else yapılarıyla kullanıcıdan alınan verilere bağlı olarak farklı işlemlerin nasıl tetikleneceğini uyguladım. Ayrıca karşılaştırma ve mantıksal operatörlerin kullanımına hakim oldum.

🔄 Proje 5: Döngüler (Loops)

Bu projede tekrarlayan işlemleri yönetmek için for, while ve foreach döngülerini derinlemesine inceledim. Döngü kontrol değişkenleri, iterasyon yapısı, break/continue anahtar kelimeleri ve performans açısından doğru döngü seçimi gibi konular üzerinde çalıştım.

🛠️ Proje 6: Metotlar (Methods)

Kodun yeniden kullanılabilirliğini ve modülerliğini artırmak için fonksiyon tasarımını öğrendim.
Parametre alan, geriye değer döndüren metotlar (return ifadeleri), metot aşırı yükleme (overloading) ve erişim belirleyicilerini kullanarak daha düzenli bir yapı oluşturmayı amaçladım.

🎓 Proje 7: Foreach Döngüsü ile Sınav Sistemi

Koleksiyonlar üzerinde dolaşmayı sağlayan foreach yapısını kullanarak bir sınav değerlendirme sistemi geliştirdim. Öğrencilerin notlarını listeleyip ortalama hesaplamaları yaparak koşullu değerlendirme süreçlerini programladım. Veri setleri üzerinde güvenli iterasyon yapmanın önemini öğrendim.

🎗️ Proje 8: Geriye Değer Döndüren Fonksiyonlar

Bu projede, kullanıcıdan alınan verileri işleyen ve sonuç üreten fonksiyonlar yazdım.
Fonksiyonel programlama mantığına uygun şekilde girdiyi işleyip uygun dönüş değerini sağlayan yapılar oluşturdum. Ayrıca metot mimarisi, iş mantığı ayrımı (business logic separation) ve hesaplamalı fonksiyon tasarımı gibi konuları pekiştirdim.

💾 Proje 9: Veritabanı Tabanlı Ürün–Kategori Bilgi Sistemi

Bu projede ADO.NET mimarisi üzerinden SQL Server ile bağlantı kurarak temel veritabanı işlemlerini gerçekleştirdim.
Kullandığım teknolojiler ve kazanımlar:

SqlConnection ile veritabanı bağlantısı oluşturma
SqlCommand ile SELECT sorguları çalıştırma
SqlDataReader kullanarak satır bazlı veri okuma
Kullanıcıdan alınan tablo/ad bilgilerinin dinamik olarak işlenmesi
Temel veri modelleme mantığını kavrama

Bu proje, veritabanından veri çekme, listeleme ve tablo yapısını anlama konusunda pratik yapmamı sağladı.

📊 Proje 10: Menü Sipariş İşlem Paneli (CRUD İşlemleri)

Bu projede SQL tabanlı bir ürün ve kategori yönetim sistemi geliştirdim. Temel CRUD operasyonlarını uygulayarak tam işlevli bir yönetim paneli oluşturdum.

Gerçekleştirdiğim teknik işlemler:

Create: INSERT komutları ile yeni ürün/kategori ekleme
Read: SELECT sorguları ile listeleme
Update: UPDATE komutları ile veri güncelleme
Delete: DELETE işlemleri ile kayıt silme
Form üzerinde kullanıcıdan alınan verileri SQL’e parametreli şekilde ileterek SQL Injection güvenliğini sağlama
Katmanlı mimarinin temel mantığını kavrama (UI → Data Layer akışı)

Bu proje, gerçek bir yönetim paneli oluşturma deneyimi kazandırdı.

🌍 Proje 11: EfTravel – Entity Framework ile İstatistik Paneli

Bu projede Entity Framework kullanarak bir seyahat veritabanı üzerinde istatistiksel veri analizleri yaptım ve sonuçları Windows Forms arayüzünde görselleştirdim.
<img width="824" height="428" alt="Ekran görüntüsü 2025-11-15 203924" src="https://github.com/user-attachments/assets/11c6a318-41c3-4ac1-91bd-2e9d95d27a08" />


Teknik olarak uyguladığım konular:

Entity Framework DbContext yapısını kullanarak ORM tabanlı sorgular yazma
LINQ ile filtreleme, sıralama, grup bazlı analizler yapma
Toplam kapasite, rehber sayısı, şehir bazlı filtreler gibi istatistiksel değerlerin hesaplanması
Maksimum kapasite/fiyat gibi metrikler üzerinden aggregate functions (Max, Min, Average) kullanımı
Form üzerinde label, textbox, chart gibi kontrolleri dinamik olarak veriyle doldurma
Verileri kullanıcıya gerçek zamanlı gösteren istatistiksel panel tasarımı

Bu proje sayesinde hem ORM kullanımı hem de veriyi görselleştirme konusunda ileri seviye pratik yapmış oldum.
