# Hafta 5 — Lab 5 · SBOM / CVE / Patch · SWOT Analizi

**Proje makinesi:** CMAK Tek Kirişli Köprülü Vinç (SAMİB) · **Hazırlayan:** Yusuf Dursun · 230541104 · Gündüz B

Doldurulmuş föy: [Lab5-SBOM-CVE-Patch.pdf](Lab5-SBOM-CVE-Patch.pdf)

| | Olumlu | Olumsuz |
|---|---|---|
| **İç** | **Güçlü Yönler (S)**<br>• Üreticiden alınan SBOM ile bileşenler görünür<br>• Üç şartlı (var / sürüm / ulaşılabilir) net karar akışı<br>• Önce ulaşılabilirliği kesme: üretim durmadan risk azaltılıyor<br>• Yama öncesi test + yedek + geri dönüş planı | **Zayıf Yönler (W)**<br>• Kurulu firmware (2.4) kritik zafiyetli<br>• Zafiyetli servis ağda açık, 4G modül internete açık<br>• Test düzeneği üreticiye bağımlı<br>• Emniyete dokunan yamada yeniden validasyon zaman ve maliyet getiriyor |
| **Dış** | **Fırsatlar (O)**<br>• Üreticinin onaylı yamasının mevcut olması<br>• SBOM ve CVE takibinin sürekli zafiyet yönetimine dönüşmesi<br>• CRA ile üreticinin güvenlik güncellemesi yükümlülüğü<br>• Kararların Evidence Pack EP 09 · 10 · 11'e girmesi | **Tehditler (T)**<br>• CVSS 9.8: aktif istismar ve uzaktan ele geçirme riski<br>• Test edilmemiş yamanın aşırı yük/limit fonksiyonunu bozması<br>• Yama gecikirse telafi edici önlemlerin zamanla gevşemesi<br>• Aynı bileşeni kullanan diğer vinçlere yayılma |
