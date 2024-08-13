# 🌦 Hava Durumu Uygulaması #
Bu proje, Python ve PyQt5 kullanarak basit bir hava durumu uygulaması oluşturur. Uygulama, bir şehir adı girildiğinde o şehir için anlık hava durumu bilgisini OpenWeatherMap API üzerinden alır ve kullanıcıya gösterir.

# 📋 Özellikler
Şehir Bazlı Hava Durumu Sorgulama: Kullanıcının girdiği şehir adı üzerinden anlık hava durumu bilgilerini getirir.
Hava Durumu Detayları: Sıcaklık, hava durumu açıklaması ve saat bilgilerini görüntüler.
Kullanıcı Dostu Arayüz: PyQt5 ile hazırlanmış sade ve kullanımı kolay bir arayüz sunar.

# 🛠 Kullanılan Teknolojiler
Python: Ana programlama dili.
PyQt5: Kullanıcı arayüzü geliştirmek için kullanılır.
requests Modülü: API çağrıları yapmak için kullanılır.
OpenWeatherMap API: Hava durumu verilerini almak için kullanılır.

# 📖 Proje Adımları
API Anahtarının Eklenmesi: Projede, hava_durumunu_al fonksiyonundaki api_anahtari değişkenine OpenWeatherMap API anahtarınızı ekleyin.
Şehir Adı Girişi: Kullanıcı, şehir adını girerek Ara butonuna tıklar.
Coğrafi Konum Bilgisi Alınması: Şehir adı üzerinden enlem ve boylam bilgileri alınır.
Hava Durumu Bilgilerinin Alınması: Enlem ve boylam bilgilerine göre hava durumu verileri alınır.
Verilerin Gösterilmesi: Hava durumu verileri, frmDurum arayüzünde kullanıcıya gösterilir.

# 🚀 Nasıl Kullanılır
Projeyi bilgisayarınıza klonlayın veya indirin.
Python'un ve gerekli modüllerin (PyQt5, requests) yüklü olduğundan emin olun.
main.py dosyasını çalıştırarak uygulamayı başlatın.

# 📄 Uyarılar
API Anahtarı: OpenWeatherMap API anahtarınızı projeye eklemeyi unutmayın.
Şehir Adı Doğruluğu: Girilen şehir adının doğru olması gerekmektedir, aksi halde uygulama hata verebilir.
Hata Yönetimi: API taleplerinde oluşabilecek hatalar için try-except blokları kullanılarak kullanıcı bilgilendirilir.
