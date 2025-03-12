# Engelden Kaçan Robot – Öneri Raporu  

## 📌 1. Proje Konusu  
Bu proje, otonom hareket edebilen ve karşısına çıkan engelleri algılayarak yön değiştiren bir robotun tasarlanmasını ve geliştirilmesini amaçlamaktadır. Robot, ultrasonik sensörler 
kullanarak çevresini algılar ve uygun manevraları gerçekleştirerek yoluna devam eder. Bu proje sayesinde temel robotik, elektronik ve programlama becerileri pekiştirilecektir. 

## 🎯 2. Proje Hedefleri  
- **Engelleri Algılama:** Robot, ultrasonik sensörler yardımıyla önündeki engelleri algılayacaktır.  
- **Otonom Hareket:** Algılanan engellerden kaçınarak en uygun rotayı belirleyip ilerleyecektir.  
- **Gerçek Zamanlı Tepki:** Engellere anlık olarak tepki vererek yön değişikliği yapacaktır.  
- **Enerji Verimliliği:** Pil tüketimini optimize eden bir kontrol mekanizması oluşturulacaktır.  
- **Geliştirilebilir Altyapı:** Proje, ek özellikler (örneğin yapay zeka veya haritalandırma) eklenerek genişletilebilir olmalıdır.  

**Başarı Kriterleri:**  
✅ Robotun en az %90 doğrulukla engelleri algılayıp yön değiştirebilmesi  
✅ 1 metre mesafedeki engellere tepki süresinin 1 saniyenin altında olması  
✅ Robotun en az 30 dakika boyunca kesintisiz çalışabilmesi  

## ⏳ 3. Tahmini Zaman Çizelgesi  

Proje Planlama ve Araştırma: 10 gün
Devre Şeması ve Bileşen Seçimi: 7 gün
Donanım Montajı: 8 gün
Arduino Kodlaması: 15 gün
Testler ve Hata Giderme: 10 gün
Nihai Testler ve Optimizasyon: 5 gün
Rapor ve Dökümantasyon: 5 gün
**Toplam Süre: 60 Gün**

## 🛠️ 4. Kaynak Planlaması  

## 📌 Proje Ekibi ve Görev Dağılımı  

### Aybüke Eraydın – *Kodlama*  
- Arduino kodlarını yazma  
- Motor sürücü ve kontrol mekanizmalarını kodlama  

### Busenur Yıldız – *Donanım Montajı & Devre Tasarımı*  
- Sensör ve motorların Arduino'ya bağlantısını yapma  
- Devre şemasını oluşturma ve test etme  
- Enerji yönetimi ve pil bağlantılarını sağlama  

### Sevgi Nur Öksüz – *Sensör Entegrasyonu*  
- Sensörlerden gelen verileri işleme  
- Kabloların düzenli yerleştirilmesini sağlama  

### Onur Kerem – *Test & Optimizasyon*  
- Robotun hareketlerini test etme  
- Engelleri algılama hassasiyetini ayarlama  
- Hata tespiti ve optimizasyon önerileri geliştirme

**Kullanılacak Ekipmanlar:**  
- **Arduino Uno**  
- **HC-SR04 Ultrasonik Mesafe Sensörü**  
- **L298N Voltaj Regulatörlü Çift Motor Sürücü Kartı**  
- **Çok Amaçlı Robot Platformu**  
- **Li-Po pil**  
- **6’lı AA Pil Yuvası**
- **Jumper** 

**Yazılım ve Geliştirme Araçları:**  
- **Arduino IDE**  
- **Tinkercad veya Proteus (Devre Simülasyonu için, opsiyonel)**  

**Tahmini Maliyet:**  
- Elektronik bileşenler: **500 - 1000₺**  
- Robot şasisi ve motorlar: **300 - 600₺**  
- Toplam tahmini maliyet: **800 - 1600₺**  

## ⚠️ 5. Risk Analizi  

### 1. Sensörlerin Yanlış Okuma Yapması  
- **Olasılık:** Orta  
- **Etki:** Yüksek  
- **Çözüm Önerisi:** Sensör hassasiyeti artırılmalı, testler yapılmalı.  

### 2. Motor Sürücünün Hatalı Çalışması  
- **Olasılık:** Düşük  
- **Etki:** Orta  
- **Çözüm Önerisi:** Bağlantılar kontrol edilmeli, alternatif sürücüler test edilmeli.  

### 3. Enerji Yetersizliği  
- **Olasılık:** Orta  
- **Etki:** Yüksek  
- **Çözüm Önerisi:** Daha yüksek kapasiteli pil kullanılmalı.  

### 4. Kod Hataları ve Optimizasyon Sorunları  
- **Olasılık:** Orta  
- **Etki:** Yüksek  
- **Çözüm Önerisi:** Kod düzenli olarak test edilmeli ve hata ayıklama yapılmalı.  

### 5. Fiziksel Engellere Çarpma  
- **Olasılık:** Yüksek  
- **Etki:** Orta  
- **Çözüm Önerisi:** Sensörlerin menzili artırılmalı, daha hassas ölçüm yapılmalı.  

## 💰 6. Ticari Potansiyel  
Bu robot, çeşitli endüstriyel ve günlük yaşam uygulamalarında kullanılabilir:  
- **Akıllı Ev Robotları:** Evin içinde engellerden kaçınarak temizlik yapabilen robot süpürgelere temel oluşturabilir.  
- **Otonom Araç Teknolojileri:** Engellerden kaçan sistemler, otonom araç geliştirme süreçlerinde temel bir modül olarak kullanılabilir.  
- **Eğitim ve STEM Projeleri:** Robotik ve programlama öğrenmek isteyen öğrenciler için harika bir eğitim aracı olabilir.  
- **Endüstriyel Otomasyon:** Fabrikalarda, depolarda veya dar alanlarda çalışan otonom robotlar için temel bir kontrol sistemi olarak uygulanabilir.  
