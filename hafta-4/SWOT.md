# Hafta 4 — Lab 4 · Secure Remote Access · SWOT Analizi

**Proje makinesi:** CMAK Tek Kirişli Köprülü Vinç (SAMİB) · **Hazırlayan:** Yusuf Dursun · 230541104 · Gündüz B

Doldurulmuş föy: [Lab4-Secure-Remote-Access.pdf](Lab4-Secure-Remote-Access.pdf)

| | Olumlu | Olumsuz |
|---|---|---|
| **İç** | **Güçlü Yönler (S)**<br>• Hedef mimaride beş ilke birlikte (jump server, VPN, MFA + kişisel hesap, kayıt, varsayılan kapalı)<br>• Emniyet bağımsızlığı: Safety PLC ve fren devresi hardwired, uzaktan yazılamaz<br>• GR-1…GR-5 ile ölçülebilir gereksinimler<br>• Uzaktan hareket komutu ve emniyet reset'i yasak | **Zayıf Yönler (W)**<br>• Mevcut mimaride modül internete doğrudan açık, 7/24<br>• Oturum kaydı yok, paylaşılan admin/admin hesabı<br>• Geçiş için jump server, VPN, güvenlik duvarı gibi ek altyapı ve maliyet gerekiyor<br>• Varsayılan kapalı model acil arızada servis süresini uzatabilir |
| **Dış** | **Fırsatlar (O)**<br>• Üreticinin (Çakmak Vinç) güvenli uzak servis modeline geçmesi<br>• Merkezi log ile olay incelemesi ve CRA uyumu<br>• Gereksinimlerin Evidence Pack EP 02 + EP 06'ya girmesi<br>• Aynı modelin fabrikadaki diğer makinelere uygulanması | **Tehditler (T)**<br>• VPN/jump server'ın kendisindeki zafiyetler<br>• MFA yorgunluğu veya oltalama ile kimlik çalınması<br>• Üçüncü taraf servis personelinin hesabını paylaşması<br>• "Geçici" açılan bağlantının açık unutulması |
