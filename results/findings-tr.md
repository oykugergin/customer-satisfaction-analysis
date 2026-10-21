# Analiz bulguları — sentetik veri

Bu rapor Python ile üretilmiştir. SPSS çıktısı değildir. Gerçek müşteri davranışını temsil etmez.

## Soru ve yöntem
Hizmet kanallarında memnuniyet düzeyi nasıl farklılaşıyor? 120 sentetik kayıt üzerinde frekanslar, kanal ortalamaları ve memnuniyet dağılımları incelendi. 4 veya 5 puan verenler bu demo için “memnun” olarak tanımlandı. Oranların paydası ilgili kanaldaki tüm kayıtlardır. Ağırlıklandırma uygulanmadı.

| Kanal | n | Memnuniyet /5 | Memnun sayısı | Memnun oranı | Kolaylık /5 | Süre (dk) |
|---|---:|---:|---:|---:|---:|---:|
| In-store | 47 | 3.74 | 31 | %66.0 | 3.96 | 7.52 |
| Online | 47 | 4.04 | 35 | %74.5 | 4.15 | 6.23 |
| Phone | 26 | 3.50 | 12 | %46.2 | 3.31 | 6.95 |

## Yorum
Bu örnek veride Online kanalının memnuniyet ve kullanım kolaylığı ortalamaları en yüksek, Phone kanalının ortalamaları en düşüktür. Gerçek bir araştırmada telefon kanalındaki hizmet deneyimi için ek sorular sorulması değerlendirilebilir; bu demo operasyonel karar için kanıt oluşturmaz.

## Sınırlılıklar
- Kanal grupları eşit büyüklükte değildir; oranlar grup içinden hesaplanır.
- 1–5 puanlar sıralı ölçektir. Ortalamalar dağılım grafiğiyle birlikte betimleyici amaçla sunulmuştur.
- Farklar için anlamlılık testi yapılmadı; nedensellik veya evrene genelleme iddiası yoktur.
- Sürenin memnuniyeti etkilediği bu karşılaştırmayla gösterilemez.
- Tavsiye puanı NPS olarak sunulmadı. Bu veri setinde 8–10 puanlı kayıt yoktur; bu durum gerçek bir müşteri araştırmasına ait sonuç değildir.

## Veri kalitesi
Eksik hücre: 0; yinelenen kayıt kimliği: 0. Kanal, yaş grubu, puan aralığı ve pozitif süre kontrolleri geçti. Ayrıntılar quality-checks.json dosyasındadır.
