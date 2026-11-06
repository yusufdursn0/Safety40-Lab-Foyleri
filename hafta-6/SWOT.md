# Hafta 6 — Lab 6 · CRA Incident Simulation · SWOT Analizi

**Proje makinesi:** CMAK Tek Kirişli Köprülü Vinç (SAMİB) · **Hazırlayan:** Yusuf Dursun · 230541104 · Gündüz B

Doldurulmuş föy: [Lab6-CRA-Incident-Simulation.pdf](Lab6-CRA-Incident-Simulation.pdf)

| | Olumlu | Olumsuz |
|---|---|---|
| **İç** | **Güçlü Yönler (S)**<br>• "Önce emniyet, hemen sonra kanıt": yük güvenle indiriliyor, vinç kilitleniyor (LOTO)<br>• Cihaz kapatılmadan izolasyon: bellekteki kanıt korunuyor<br>• Test ağırlığı, limit, fren ve acil stop testleriyle somut doğrulama<br>• 15 dk / 2 saat / 24s / 72s / 14 gün net zaman çizelgesi ve rol dağılımı | **Zayıf Yönler (W)**<br>• Paylaşılan servis hesabı nedeniyle girişi kimin yaptığı belirsiz<br>• Olay ancak sabah fark edildi: gece izleme ve alarm yok<br>• Referans checksum ve kalibrasyon yedeği yoksa doğrulama zorlaşıyor<br>• Vincin kullanım dışı kalması üretimi durduruyor |
| **Dış** | **Fırsatlar (O)**<br>• CRA ile üreticinin (Çakmak Vinç) bildirim ve düzeltme yükümlülüğü<br>• Üretici PSIRT'i ile ortak kök neden analizi<br>• Olaydan çıkan dersle uzak erişim ve log altyapısının iyileşmesi<br>• Akışın Evidence Pack EP 13 Incident Response'a girmesi | **Tehditler (T)**<br>• "Resetleyip devam edelim" baskısıyla kanıtın silinmesi<br>• Değişen aşırı yük/kalibrasyon ayarı fark edilmezse yük düşmesi<br>• Saldırganın başka hesap veya kalıcı erişim bırakmış olması<br>• Aynı zafiyetin diğer vinçlere ve müşterilere yayılması |
