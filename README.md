# 🎓 Öğrenci Bilgi Sistemi

Bu sistem, üniversite düzeyinde öğrenci-ders-hoca etkileşimini yönetmek amacıyla geliştirilmiş bir **ders seçimi simülasyonudur**. Proje, masaüstü uygulaması olarak **C# dili** ve **Windows Forms** teknolojisi ile geliştirilmiştir.

---

## ✨ Özellikler

### 👨‍🎓 Öğrenci Paneli Özellikleri

- 🔐 Öğrenci girişi sonrası bireysel panel erişimi  
- 📄 Transkript PDF yükleme ve derslerin otomatik olarak sistem veritabanına aktarılması  
- 📋 Önceki alınan ders ve notların görüntülenmesi  
- 🧭 Almak istenen derslere göre hoca listesi ve ilgi alanı filtrelemesi  
- 🧑‍🏫 Farklı hocalar arasından ders talep etme  
- ⛔ Talep onaylanmadan iptal etme imkânı  
- 📩 Hoca ile birebir mesajlaşma  
- ✅ İlk onaylayan hocaya dersin atanması ve panelde görüntülenmesi  

---

### 👨‍🏫 Hoca Paneli Özellikleri

- 🏷️ Kendi ilgi alanlarını sisteme kaydetme  
- 📥 Ders talebinde bulunan öğrencileri listeleme  
- 🕶️ Talebi onaylanmamış öğrencileri görüntüleme  
- 📚 Öğrencinin önceki aldığı dersleri ve notlarını inceleyebilme  
- 📊 Kendi belirlediği formülle öğrenci uygunluk sıralaması yapma  
- 🔁 Öğrenciye ders önerme (dersi alması için talep oluşturma)  
- ✅ Öğrencinin yanıtına göre dersin eklenmesi  
- 🔢 Kontenjan yönetimi (toplam öğrenci sayısına göre)  
  - Aynı öğrencinin farklı dersleri ayrı kontenjandan düşülür  

---

### 🧑‍💼 Yönetici Paneli Özellikleri

- 🔧 Tüm kullanıcı (öğrenci & hoca) bilgilerini görüntüleme, güncelleme, silme  
- 🛠️ Sistem parametreleri ve süreç ayarlarını yönetme (1. ve 2. aşama süreçler)  
- 📚 İlgi alanı kayıt & güncelleme  
- 📝 Öğrenci-hoca taleplerini geçmişiyle birlikte inceleyip elle işlem yapabilme  
- 🔐 "Bir öğrencinin tüm dersleri tek bir hocadan alması" kuralını aktif/pasif yapabilme  
- 🧪 Otomatik öğrenci üretimi (maks. 50 öğrenci)  
  - Rastgele notlar ve ders bilgileriyle birlikte  
  - PDF formatıyla uyumlu olacak şekilde veritabanına ekleme  

---

## 🔄 Atama Yöntemleri (Süreç Sonunda Uygulanır)

- 🎲 **Rastgele Atama:** Öğrenciler rastgele sıralanarak hocalara atanır  
- 🧮 **Not Ortalamasına Göre Atama:** En yüksek ortalamadan başlanarak atanır  
- 📘 **Belirli Derslere Göre Atama:** Yönetici tarafından seçilen en fazla 5 derse göre özel formüle dayalı atama yapılır  

> ⚠️ **Not:** Bu atama işlemleri, yöneticinin belirlediği anlaşma süresi sona erdikten sonra başlatılır.

---

## 🛠️ Kullanılan Teknolojiler

- C#  
- Windows Forms  
- PostgreSQL  

