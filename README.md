# Otonom-Engel-Algilayan-Robot-Araba
Engelden Kaçan Robot Araba
Bu proje, Arduino Uno ve HC-SR04 Ultrasonik Sensör kullanarak engelleri algılayan ve yön değiştiren bir robot araba geliştirmeyi amaçlamaktadır. Robot, mesafe sensörü ile önündeki engelleri algılayarak uygun bir manevra gerçekleştirir.

## 🔧 Proje Açıklaması
Robot, HC-SR04 Ultrasonik Sensör yardımıyla çevresindeki nesnelerin mesafesini ölçer. Eğer bir engel belirlenen mesafeden daha yakınsa, robot geri hareket eder ve engelden kaçmak için sağa döner. Engel yoksa, düz ileri hareket etmeye devam eder.

## Projenin temel bileşenleri:

Arduino Uno: Mikrodenetleyici kartı
HC-SR04 Ultrasonik Mesafe Sensörü: Engelleri algılar
L298N Motor Sürücü Kartı: DC motorları kontrol eder
DC Motorlar ve Tekerlekler: Robotun hareketini sağlar
Pil ve Pil Yuvası: Güç kaynağı
Bu sistem, engellerden kaçan basit bir otonom robot için temel bir algoritma kullanmaktadır.

## 🛠 Kullanılan Malzemeler
Malzeme	Açıklama
Arduino Uno	: Mikrodenetleyici kartı
HC-SR04 Ultrasonik Sensör :	Robotun önündeki engelleri algılar
L298N Motor Sürücü Kartı :	DC motorların hızını ve yönünü kontrol eder
DC Motorlar (x2) :	Robotun tekerleklerini döndürür
Robot Platformu	Şasi ve tekerleklerin montajı için kullanılır
6'lı AA Pil Yuvası :	Arduino ve motorlar için güç sağlar
Alkalin veya Li-Po Pil	: Robotun çalışması için enerji kaynağı (Li-Po önerilir)
Jumper Kabloları :	Devre bağlantıları için kullanılır

##⚙ Çalışma Prensibi
Ultrasonik sensör, belirli aralıklarla çevresindeki engellerin mesafesini ölçer.
Eğer önünde bir engel algılarsa (mesafe belirli bir eşiğin altındaysa), robot geri gider ve sağa döner.
Engel yoksa, robot doğrudan ileri hareket eder.
Bu döngü sürekli tekrarlanarak robotun engellerden kaçması sağlanır.
