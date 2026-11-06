# Hafta 7 — Lab 7 · AI Safety Challenge · SWOT Analizi

**Proje makinesi:** CMAK Tek Kirişli Köprülü Vinç (SAMİB) · **Hazırlayan:** Yusuf Dursun · 230541104 · Gündüz B

Doldurulmuş föy: [Lab7-AI-Safety-Challenge.pdf](Lab7-AI-Safety-Challenge.pdf)

| | Olumlu | Olumsuz |
|---|---|---|
| **İç** | **Güçlü Yönler (S)**<br>• Prediction ≠ Safety: aşırı yük, limit ve acil stop zinciri YZ'den tamamen ayrı<br>• YZ'nin OK'i tek başına kaldırma izni vermiyor, sapancı onayı zorunlu<br>• Yavaş "deneme kaldırması" + yük hücresi ile ikinci kontrol<br>• Net güven eşikleri (≥%95 / %80–95 / &lt;%80) ve fallback | **Zayıf Yönler (W)**<br>• Model kancadaki zor açılarda ve kötü ışıkta yanılabilir<br>• Eşiklerin belirlenmesi için yeterli validasyon verisi gerekiyor<br>• İnsan onayı ve yavaş kaldırma çevrim süresini uzatıyor<br>• Kamera ve model bakımı ek iş yükü getiriyor |
| **Dış** | **Fırsatlar (O)**<br>• Hatalı sapan bağlamadan kaynaklı kazaların azalması<br>• Kaldırma kayıtlarıyla eğitim ve denetim verisi oluşması<br>• Yöntemin fabrikadaki diğer vinç ve kaldırma ekipmanlarına uygulanması<br>• Kararların Evidence Pack EP 03 + EP 15'e girmesi | **Tehditler (T)**<br>• Kamera görüntüsünün bozulması veya sahte görüntü verilmesi<br>• Operatörün YZ'ye aşırı güvenip kendi kontrolünü bırakması<br>• Model kayması (drift) ile güven değerlerinin zamanla düşmesi<br>• YZ'nin yanlışlıkla emniyet fonksiyonu gibi görülmesi |
