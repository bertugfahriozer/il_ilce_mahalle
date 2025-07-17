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
