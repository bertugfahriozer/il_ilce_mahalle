# Türkiye İl, İlçe ve Mahalle Listesi (JSON)

Bu proje, **Türkiye'deki tüm il, ilçe ve mahalleleri** içeren kapsamlı bir JSON veri seti sunar. Veriler, resmi kaynaklardan (TÜİK, İçişleri Bakanlığı) alınan mahalle listelerine dayanarak işlenmiş ve hiyerarşik bir yapı ile sunulmuştur.

---

## 🔍 Yapı (JSON Formatı)

```json
{
  "İL_ADI": {
    "İLÇE_ADI": [
      "Mahalle Adı 1 Mah.",
      "Mahalle Adı 2 Mah.",
      ...
    ]
  }
}
```

## Örnek

```json
{
  "ADANA": {
    "ALADAĞ": [
      "BOZTAHTA Mah.",
      "BÜYÜKSOFULU Mah.",
      ...
    ]
  }
}
```

## 📁 Dosya

- il-ilce-mahalle.json – Tüm Türkiye’yi kapsayan güncel mahalle verisi.

## 📌 Kullanım Alanları

Bu JSON dosyası aşağıdaki gibi projelerde kullanılabilir:

-	Adres seçimi formları
-	Coğrafi konumlu uygulamalar (map, delivery, vs.)
-	Veri analizi ve demografik raporlar
-	e-Devlet entegrasyonları
-	E-ticaret & kargo sistemleri

## ⚙️ Üretim Süreci

Veri, .csv formatındaki resmi mahalle listesinden Python ile işlenmiş ve il → ilçe → mahalle yapısına dönüştürülmüştür. Her mahalle adı " Mah." ekiyle tamamlanmıştır.

## 📬 Katkıda Bulunmak

Eksik veya güncel olmayan veri tespit ederseniz PR gönderebilir veya issue açabilirsiniz.

## 📜 Lisans

Bu veri dosyası açık kaynak olup dilediğiniz projede ticari veya bireysel olarak kullanılabilir. Kaynak belirtmeniz rica olunur.
