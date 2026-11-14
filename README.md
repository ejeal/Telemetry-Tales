# Telemetry Tales

> **Durum:** Proje tamamlandı.  
> **Kategori:** Terk Edilmiş Teçhizat Hikayeleri | Hikaye anlatımı, görsel içerik  
> **Takım Büyüklüğü:** 3 kişi  
> **Deadline:** 15 Kasım Pazar günü, saat 23:59  

---

## 1. Yönetici Özeti

**Telemetry Tales**, NASA'nın geçmiş insansız ve insanlı uzay görevlerinde kullandığı ve Ay, Mars ile derin uzayda bıraktığı öncü araçların (Apollo 11, Lunokhod 1, Chang'e 4, Viking 1, Sojourner, Opportunity, Perseverance) teknik arşiv verilerini genç kitleler için hikâyeleştiren interaktif bir web platformudur. 

Proje; açık erişimli ancak karmaşık teknik arşiv verilerini, modern karanlık tema (`darkglassmorphism`), iki dilli destek (İngilizce/Türkçe), canlı telemetri simülasyonları ve detaylı modal kartlar eşliğinde ortaöğretim ve genç bilim meraklılarına sunmaktadır.

---

## 2. Problem ve Çözüm

### Problem Tanımı
NASA, 1960'lardan bu yana Ay'da, Mars'ta ve derin uzayda Apollo iniş modülleri, Ay araçları, Surveyor ve Viking iniş araçları, Spirit ile Opportunity gezginleri ve Pioneer sondaları gibi çok sayıda donanım bıraktı. Bu donanımların sağladığı veriler NSSDCA gibi kaynaklarda herkese açık, ancak teknik metinler ve tarih içerikleri biçiminde duruyor. Okul çağındaki ve uzaya meraklı genç kitle ise uzay görevlerini çoğunlukla devam eden görevler üzerinden tanıyor. 

Sorun bilginin yokluğu değil, anlatılış biçiminin hedef kitleye ulaşmamasıdır. Donanımın mühendisliği ile ondan elde edilen keşifler arasındaki bağ bir hikâye olarak kurulmadığı için bu araçlar unutulmuş durumda.

### Soru - Cevap Analizi
* **Kimin sorunu?** Uzay ve havacılığa ilgi duyan, ortaöğretim düzeyindeki genç bilim meraklıları, öğrenciler ve eğitmenler.
* **Sorun ne?** NASA'nın geçmiş insansız uzay görevlerinde kullandığı araçların ve verilerin yalnızca teknik arşiv formatında sunulması; mühendislik ile keşif arasındaki bağın gençlere hitap eden bir hikâye diliyle anlatılmaması.
* **Neden önemli?** Bugünkü ve gelecekteki Ay/Mars görevleri bu öncü araçların mirası üzerine kuruluyor. Geçmiş görevlerin unutulması, genç neslin bilim ve uzay mühendisliğine olan ilgisini ve tarihsel bağlamını zayıflatıyor.

### Çözüm
Projenin mevcut prototipinde yer aldığı üzere; Ay ve Mars yüzeyinde bırakılmış 13 ikonik araç (*Apollo 11, Apollo 12, Apollo 15, Surveyor Landers, Sojourner Rover, Spirit & Opportunity, Viking 1 & 2 Landers, Phoenix & InSight Landers, Ingenuity Helicopter, NEAR Shoemaker, Pioneer 10 & 11, Kepler Space Telescope, Dawn Spacecraft*) kataloglanmıştır.

Geliştirilen web arayüzü; Türkçe/İngilizce dil desteği, gerçek zamanlı sinyal/gecikme simülasyonları, gezegen filtreleme sekmeleri ve her araca ait teknik istatistik/hikâye pencereleriyle teknik verileri gençlerin kolayca kavrayabileceği bir deneyime dönüştürmektedir.

---

## 3. Vizyon & Misyon

* **Vizyon:** Uzay tarihinin unutulmuş donanımlarını genç nesillerin gözünde yeniden canlandırarak, geçmişin mühendislik başarıları ile geleceğin uzay kâşifleri arasında kalıcı bir ilham köprüsü kurmak.
* **Misyon:** NASA'nın açık erişimli karmaşık görev verilerini; modern web teknolojileri, çift dilli arayüz ve canlı telemetri simülasyonlarıyla zenginleştirerek ortaöğretim düzeyindeki gençlerin dilinden anlayan etkileşimli hikâyelere dönüştürmek.

---

## 4. Hedef ve Amaçlar

1. **Genişletilmiş Veri Tabanı ve Kataloglama:** Ay (4 araç) ve Mars (9 araç) olmak üzere toplam 13 ikonik uzay aracının teknik verilerini, tarihçelerini ve keşif hikâyelerini prototip düzeyinde sisteme entegre etmek.
2. **İnteraktif & Çift Dilli Deneyim:** Kullanıcıların İngilizce ve Türkçe dilleri arasında anlık geçiş yapabilmesini, gezegen filtrelerini kullanabilmesini ve araç detaylarına modal pencerelerle ulaşabilmesini sağlamak.
3. **Canlı Telemetri Simülasyonu:** Sinyal gücü (`dBm`), Ay/Mars sinyal gecikmeleri ve yüzey sıcaklığı gibi parametreleri simüle eden canlı terminal akışı eklemek.
4. **Tam Zamanında Teslim:** Prototip sürümünü, tanıtım sunumunu ve evrensel proje dosyasını eksiksiz şekilde tamamlamak.

---

## 5. Takım Rol Dağılımı

| Rol | İsim | Sorumluluk | Yetki |
| :--- | :--- | :--- | :--- |
| **Proje Kaptanı & Hikaye/Araştırma Lideri** | Elif Ece ÖZKARA | NSSDCA veri araştırması, araçların hikaye metinlerinin oluşturulması, TR/EN çeviri içerikleri ve zaman yönetimi | Proje kapsamı, içerik onayı, final teslim kararları |
| **Frontend & Web Geliştirme Sorumlusu** | Ece ALTUNDİŞ | HTML/CSS/JS tabanlı arayüz kodlaması, dil geliştirme mantığı, modal pencereler, canlı telemetri simülasyon döngüsü ve deploy | Teknik mimari, kod deposu (GitHub) yönetimi ve canlı ortam kararları |
| **Görsel Tasarım & UI/UX Sorumlusu** | Esmanur ASAL | Karanlık tema (glassmorphism) tasarımı, gezegen sekmeleri, mobil uyumluluk ve sunum slaytları proje dosyalarının oluşturulması ve takibi | Görsel kimlik, renk paleti, tipografi ve medya varlıklarının onayı |

---

## 6. Yol Haritası / İlerleyiş

### Faz 1: Prototip Geliştirme ve 13 Araç Entegrasyonu (Tamamlandı)
* **Specific:** 13 ikonik uzay aracının prototip arayüze eklenmesi.
* **Measurable:** 13 aktif kart, modal detay görünümleri ve TR/EN dil desteği içeren çalışan HTML/JS prototipi.
* **Achievable:** Modern web teknolojileriyle hızlı ve efektif şekilde tamamlandı.
* **Time-bound:** Proje ara teslim tarihinden önce prototip olarak hazırlandı.

### Faz 2: Gelişmiş Özellikler ve Canlı Yayın
* **Specific:** Web sitesinin GitHub Pages üzerinde canlıya alınması, ek araçların eklenmesi ve UI cilalanması.
* **Measurable:** Canlı erişilebilir URL ve optimize edilmiş mobil görünüm.
* **Time-bound:** Proje teslim tarihine kadar.

### Faz 3: Sunum ve Final Teslim
* **Specific:** Proje sunum slaytlarının hazırlanması ve jüri teslimi.
* **Measurable:** 1 adet sunum dosyası ve eksiksiz proje dokümantasyonu.

---

## 7. Kısıtlar

* **Zaman Kısıtı:** Proje takvimi doğrultusunda hızlı iterasyonlar yapılarak son sürüm kararlı hale getirilmiştir.
* **İnsan Kaynağı Kısıtı:** Ekip 3 kişiden oluşmaktadır; içerik, tasarım ve frontend geliştirme işleri paralel yürütülmektedir.
* **Bütçe Kısıtı:** Sıfır bütçe ile açık kaynaklı NASA verileri ve ücretsiz hosting araçları kullanılmaktadır.

---

## 8. Risk Kayıt Defteri

| Risk Açıklaması | Olasılık (1-5) | Etki (1-5) | Risk Skoru | Önlem / Çözüm |
| :--- | :---: | :---: | :---: | :--- |
| Teknik arşiv verilerinin gençler için fazla karmaşık gelmesi | 3 | 4 | 12 (Orta) | Veriler sadeleştirilerek hikâyeleştirildi ve modal kartlara bölündü. |
| Canlı telemetri simülasyonunun tarayıcı uyumsuzluğu yaşaması | 2 | 3 | 6 (Düşük) | Saf JavaScript kullanılarak hafif ve evrensel bir yapı kuruldu. |
| Zaman yönetimi baskısı | 3 | 4 | 12 (Orta) | İş yükü takım üyeleri arasında net bir şekilde paylaştırıldı. |
