# 🧶 Stoll Desen Gezgini

[![Sürüm](https://img.shields.io/badge/S%C3%BCr%C3%BCm-v1.2-0284C7.svg)](https://github.com/gokhantr/Stoll-Desen-Gezgini/releases/latest)
[![Platform](https://img.shields.io/badge/Platform-Windows%20(x86%20%2F%20x64)-1E293B.svg)](https://github.com/gokhantr/Stoll-Desen-Gezgini/releases/latest)
[![Lisans](https://img.shields.io/badge/Lisans-%C3%9ccretsiz%20%2F%20Sekt%C3%B6r-16A34A.svg)](https://github.com/gokhantr/Stoll-Desen-Gezgini)

**Stoll Desen Gezgini**, triko desinatörleri ve teknisyenlerinin desen iş akışlarını hızlandırmak amacıyla **Gökhan Yücel** tarafından geliştirilmiş olup, sektörün ücretsiz ve sınırsız kullanımına sunulmuştur.

M1plus programının açılmasını beklemeden, yerel disklerdeki veya yerel ağdaki (UNC / paylaşımlı klasörler) tüm Stoll `.mdv` desen dosyalarını milisaniyeler içinde keşfetmenizi, önizlemenizi ve teknik analiz yapmanızı sağlar.

---

## 🚀 Doğrudan İndirme

En son güncel sürümü aşağıdaki bağlantıdan hemen indirebilirsiniz:

👉 **[Stoll Desen Gezgini - En Son Sürümü İndir (v1.2)](https://github.com/gokhantr/Stoll-Desen-Gezgini/releases/latest)**

*Kurulum gerektirmez. İndirdiğiniz `Stoll Desen Gezgini.exe` dosyasını doğrudan çalıştırabilirsiniz.*

---

## ✨ Temel Özellikler

- ⚡ **Ultra Hızlı Canlı Önizleme:** Ağır M1plus yazılımını açmaya gerek kalmadan, desenleri anında tam çözünürlüklü raster olarak inceler.
- 📁 **Gelişmiş Dosya Gezgini:** 
  - Yerel sürücüler, flash diskler ve ağ yolları (`\\sunucu\desen`) ile tam uyumlu ağaç yapısı.
  - Sık kullanılan desen klasörlerinizi tek tıkla Hızlı Erişim'e ekleme.
  - Klasör içindeki alt dizinler arasında zahmetsizce gezinme.
- 🖼️ **Liste & 200x200 Galeri Görünümü:** Desenleri alfabetik, tarihe veya dosya boyutuna göre sıralayabilir; liste veya küçük resimli galeri kutuları halinde görüntüleyebilirsiniz.
- 📏 **Hassas En / Boy İğne ve Sıra Ölçüm Aracı:**
  - Desendeki motifleri iğne iğne, sıra sıra ölçün.
  - Çerçevenin solundaki iğnenin sol kenarından sağındaki iğnenin sağ kenarına kadar kusursuz piksel hizalaması.
  - Akıllı bilgi etiketi (kenarlara gelindiğinde otomatik yön değiştirir).
- 🚀 **Akıllı M1plus Entegrasyonu:** Farklı disk ve versiyonlardaki M1plus kurulumlarını otomatik bulur, desenleri tek tıkla veya `Enter` tuşuyla açar.
- 🔄 **Otomatik GitHub Güncelleme Denetimi:**
  - Yeni bir sürüm çıktığında uygulama sizi anında uyarır ve tek tıkla yeni sürümü indirmenizi sağlar.
  - Hakkında menüsünden elle güncelleme kontrolü yapılabilir.
- 📦 **Tek Parça Taşınabilir EXE (Portable):** Kurulum, bağımlılık veya M1plus lisansı gerektirmez.

---

## 🛠️ Sistem Gereksinimleri

- **İşletim Sistemi:** Windows 10, Windows 11 (32-bit & 64-bit)
- **Ek Bileşen:** Gerekmez (Tüm çalışma zamanı kütüphaneleri exe içerisine gömülmüştür)

---

## 📝 Versiyon Notları

### v1.2
- **Modern Navigasyon Gezgini:** Eski ağaç yapısı yerine Hızlı Erişim, Bu Bilgisayar/Sürücüler ve Dinamik Alt Klasörler panellerinden oluşan modern yan menüye geçildi.
- **Tıklanabilir Breadcrumb (Ekmek Kırıntısı):** Üst başlıkta klasör yolunu tıklanabilir butonlara bölen hızlı geri/ileri navigasyon çubuğu eklendi.
- **Pencere ve Bölme Düzeni Hafızası:** Pencere boyutu, konumu, tam ekran durumu ve sütun genişlikleri (GridSplitter) kapatılırken otomatik kaydedilir ve açılışta korunur.
- **Ekran Çözünürlüğü ve DPI Koruması:** 1600x900 ve laptop ekranlarında pencere başlığının ekrandan dışarı taşması engellendi, akıllı sığdırma eklendi.
- **%56 Boyut Optimizasyonu:** Bağımsız tek parça EXE boyutu 140 MB'tan **61 MB**'a indirildi (.NET ve Stoll DLL'leri tam gömülüdür).
- **Akıllı M1plus Algılama:** Farklı sürücü ve dizinlerdeki M1plus sürümleri (8.x, 7.x vb.) Registry ve disk taramasıyla otomatik bulunur; bulunamazsa kullanıcıya manuel seçim sunulur ve hatırlanır.
- **Klavyeden Enter ile Açma:** Listede veya galeride seçili desen `Enter` tuşuna basılarak anında M1plus ile açılabilir.
- **Düşük Bellek Tüketimi (OOM Koruması):** Galeri modunda küçük resim üretimi optimize edildi, yüzlerce desen içeren klasörlerde bellek tüketimi en aza indirildi.
- **Hata Günlüğü Güvenliği:** Log ve ayar dosyaları yetki kısıtlamalarından etkilenmeyecek şekilde `%AppData%` altına taşındı.

### v1.1
- Uygulama adı "Stoll Desen Gezgini" olarak tescillendi.
- GitHub API tabanlı otomatik ve manuel sürüm denetleyici modülü entegre edildi.
- En ve boy iğne/sıra ölçüm aracının piksel sınırları ve çerçeve hizalaması kusursuzlaştırıldı.
- Arayüz renkleri ve buton hover okunabilirlik geliştirmeleri yapıldı.
- Durum çubuğu ve hakkında pencereleri sadeleştirildi.

---

## 👨‍💻 Geliştirici & İletişim

- **Geliştirici:** Gökhan Yücel
- **GitHub Reposu:** [https://github.com/gokhantr/Stoll-Desen-Gezgini](https://github.com/gokhantr/Stoll-Desen-Gezgini)
