# TAI-Tripple-AI-Project
İnsan beyninin limbik sistemi için geliştirilmiş, sıvıyla çalışabilen elektrokimyasal çipler aracılığıyla AKM (Ana Kontrol Modülü) vasıtasıyla kompleks bir şekilde çalışan hormon düzenleme yazılımı.

## Projenin Amacı
Bu proje, bireylerin yaşadığı hormonal ve duygusal problemleri (örneğin öfke patlamaları, aşırı stres) düzenleyerek yaşam kalitesini arttırmayı hedefler. Sistem, beyindeki 8 farklı bölgeye (Hipotalamus, Amigdala, OFC vs.) yerleştirilen çiplerle beraber **elektrokimyasal şok dalgaları** göndererek kompleks bir şekilde çalışır.

## Temel Özellikler
SRS dokümanımızda (v1.0) belirtilen başlıca özellikler:

* **Kritik Müdahale (FR1):** AKM, aşırı stres/öfke anında herhangi bir aracı olmadan direkt olarak müdahale eder.
* **Acil Durum Çağrısı (FR23):** Hayati risk durumunda sistem otomatik olarak acil servis çağırır.
* **Uzaktan Doktor Erişimi (FR25):** Yetkili doktorlar verilere uzaktan erişip müdahale eşiklerini ayarlayabilir.
* **Güvenlik Modu (FR30):** Çip sıcaklığı 35°C'ye ulaşırsa sistem beyni korumak için kendini yavaşlatır.
* **Çoklu Dil Desteği:** Sistem global kullanım için tasarlanmıştır.

## Mimari Yapısı
TAI yazılımı üç ana bileşenden oluşur:
1.  **Beyin Çipleri:** Beynin 8 farklı bölgesi üzerinde çalışan çipler ve uyarıcılar.
2.  **RF İletişim Modülü:** Kablosuz veri aktarım katmanı.
3.  **Ana Kontrol Modülü (AKM):** Karar veren ve komutları işleyen merkezi yazılım.

## Dokümantasyon
Projenin teknik detayları, UML diyagramları ve gereksinim analizi için aşağıdaki bağlantıyı kullanabilirsiniz:
👉 [Proje SRS Dokümanı (v1.0)](TAI_SRS_Document.pdf)

## Proje Dokümantasyonu
Detaylı teknik analiz, UML diyagramları ve gereksinim listesi için [SRS Dokümanını](TAI_SRS_Document.pdf) inceleyebilirsiniz.

---
**Geliştiriciler:** Evrim Çolakoğlu & Emirhan Cenger
