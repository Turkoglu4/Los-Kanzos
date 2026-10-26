VY-023 Teknik Servis ve Bakım Takip Sistemi

Proje Tanımı
Bu proje, teknik servise gelen cihazların kabul, onarım, yedek parça stok ve işlem takibini yapmak amacıyla geliştirilen Java tabanlı bir masaüstü uygulamasıdır.

Ekip Üyeleri
- Üye 1 Ahsen Türkoğlu - @Turkoglu4
- Üye 2 Abdurrahman Kaplan - @abdu-c
- Üye 3 Ahmet Utku Eraslan - @Ustad07-Utku
- Üye 4 Kemal Kaplan - @todestern2

Kullanılan Teknolojiler
- Java (JDK 17)
- JavaFX
- Git / GitHub

Temel İşlevler ve Veri Yapıları
- Müşteri ve Cihaz Arama: HashMap (O(1) karmaşıklığında hızlı arama için)
- Servis Kabul ve Sıra: PriorityQueue (Cihazların aciliyet durumuna göre sıralanması için)
- Yedek Parça Stok Takibi: Binary Search Tree - BST (Parça koduna göre sıralı ve hızlı arama için)
- İşlem Geçmişi: Stack (Son yapılan işlemlerin takibi ve geri al, LIFO)

Sınıf ve Düğüm Yapıları Taslağı
- Musteri: musteriId, adSoyad, telefon
- ServisKayidi: cihazId, arizaTanimi, aciliyetSeviyesi
- ParcaNode: parcaKodu, stokAdedi, sol, sag
