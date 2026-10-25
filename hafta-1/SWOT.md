# Hafta 1 — Lab 1 · Safety Architecture · SWOT Analizi

**Proje makinesi:** CMAK Tek Kirişli Köprülü Vinç (SAMİB) · **Hazırlayan:** Yusuf Dursun · 230541104 · Gündüz B

Doldurulmuş föy: [Lab1-Safety-Architecture.pdf](Lab1-Safety-Architecture.pdf)

| | Olumlu | Olumsuz |
|---|---|---|
| **İç** | **Güçlü Yönler (S)**<br>• Emniyet yolu (Safety PLC → STO + fren) normal kontrolden ayrı<br>• Yay baskılı fren: enerji kesilince yük kendiliğinden tutulur (fail-safe)<br>• Çift kanallı, kendini test eden Safety PLC (PL e / SIL 3'e kadar)<br>• Donanımsal son limit güç devresinde | **Zayıf Yönler (W)**<br>• Uzak bakım modülü normal PLC ile aynı ağda (dijital kesişim noktası)<br>• Yük hücresi kalibrasyonu yazılımda tutuluyor, değiştirilebilir<br>• Yazılımsal limitler enkodere ve PLC programına bağımlı<br>• Telsiz kumanda taklit/tekrar saldırısına açık |
| **Dış** | **Fırsatlar (O)**<br>• ISO 13849-1 / IEC 62061 ile PLr d hedefinin net tanımlanması<br>• EN 15011 / EN 13135 vinç standartlarıyla doğrulama<br>• Safety Function Map'in Evidence Pack'e (EP 03) girdi olması<br>• Emniyet ve siber güvenliği birlikte ele alan Safety 4.0 yaklaşımı | **Tehditler (T)**<br>• İnternetten 4G modül üzerinden aşırı yük eşiğinin değiştirilmesi<br>• Fren/tork parametrelerinin bozulmasıyla yük kayması<br>• HMI'dan sahte reset ile otomatik yeniden yol alma<br>• Yük düşmesi → ölüm/kalıcı yaralanma (S2) |
