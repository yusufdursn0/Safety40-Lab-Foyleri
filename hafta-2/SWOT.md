# Hafta 2 — Lab 2 · IEC 62443 Mini Workshop · SWOT Analizi

**Proje makinesi:** CMAK Tek Kirişli Köprülü Vinç (SAMİB) · **Hazırlayan:** Yusuf Dursun · 230541104 · Gündüz B

Doldurulmuş föy: [Lab2-IEC-62443-Mini-Workshop.pdf](Lab2-IEC-62443-Mini-Workshop.pdf)

| | Olumlu | Olumsuz |
|---|---|---|
| **İç** | **Güçlü Yönler (S)**<br>• Emniyet bölgesi (Z3, SL 3) ayrı ve en sıkı conduit (C3: yalnız okuma) ile korunuyor<br>• Varlıklar kritikliğe göre net gruplandı, hedef SL'ler tanımlandı<br>• Uzak erişim için jump server + VPN + MFA + kişisel hesap kararı<br>• Buluta yalnız giden, TLS şifreli veri | **Zayıf Yönler (W)**<br>• Mevcut durumda uzak bakım modülü kontrol bölgesinde (Z2)<br>• HMI port 80, kimlik doğrulamasız web arayüzü<br>• Wi-Fi parolası kartonda, 2 kilitsiz USB<br>• Paylaşılan admin/admin servis hesabı |
| **Dış** | **Fırsatlar (O)**<br>• IEC 62443 mantığıyla segmentasyonun standart bir çerçeveye oturması<br>• Zone/Conduit diyagramının Evidence Pack EP 05'e girmesi<br>• Oturum kayıtlarının CRA bildirimi ve olay incelemesinde kanıt olması<br>• Üreticiyle (Çakmak Vinç) ortak güvenli servis modeli | **Tehditler (T)**<br>• İnternetten port taramasıyla 4G modemin bulunması<br>• Tek adımda kontrol bölgesinden Safety PLC'ye geçiş<br>• Telsiz sinyalinin taklit edilmesi (C5)<br>• Tesis yakınından Wi-Fi üzerinden ağa sızma |
