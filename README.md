** 🌦 Hava Durumu Uygulaması ** 
Bu proje, Python ve PyQt5 kullanarak basit bir hava durumu uygulaması oluşturur. Uygulama, bir şehir adı girildiğinde o şehir için anlık hava durumu bilgisini OpenWeatherMap API üzerinden alır ve kullanıcıya gösterir.

** 🛠️ Kullanım**
API Anahtarınızı Ekleyin: hava_durumunu_al fonksiyonundaki api_anahtari değişkenine OpenWeatherMap API anahtarınızı ekleyin.

** 📋 Dikkat Edilmesi Gerekenler **
API Anahtarı: Proje düzgün çalışması için OpenWeatherMap API anahtarınızı eklemeyi unutmayın.

Şehir Bilgisi:
Kullanıcı, arama yaparken şehir adını doğru girmelidir. Yanlış şehir adı girildiğinde hata mesajı gösterilir.

** 🧩 Proje Yapısı**
├── donusumler/
│   ├── frmGirisUİ.py  # Giriş ekranı arayüzü
│   └── frmDurumUİ.py  # Durum ekranı arayüzü
├── main.py  # Uygulama ana dosyası
└── README.md  # Proje dokümantasyonu

** 🎨 Arayüz Detayları **
Giriş Ekranı: Şehir adını girin ve Ara butonuna tıklayın. Bu ekran, frmGiris sınıfı tarafından yönetilir.
Durum Ekranı: Seçilen şehir için hava durumu detaylarını gösterir. Bu ekran, frmDurum sınıfı tarafından yönetilir.

🧪 Testler
Bu proje için özel test senaryoları yazılmamıştır. Ancak, test yapmak isterseniz, hava_durumunu_al fonksiyonunu çeşitli şehir isimleriyle deneyebilirsiniz.

💡 İpuçları
Uygulamayı geliştirmek için Qt Designer kullanarak arayüzü özelleştirebilir ve yeni özellikler ekleyebilirsiniz.
API isteği yaparken try-except bloklarını kullanarak hata yönetimini geliştirebilirsiniz.
