# 📱 Sentiric SIP Client SDK

[![Status](https://img.shields.io/badge/status-vision-lightgrey.svg)]()

**Sentiric SIP Client SDK**, harici uygulamaların (web, mobil) Sentiric platformuyla SIP protokolü üzerinden sesli iletişim kurmasını sağlayan bir istemci kütüphanesidir.

**Bu, çalışan bir servis değil, diğer uygulamalara entegre edilmek üzere tasarlanmış bir kütüphanedir.**

## 🎯 Temel Sorumluluklar (Vizyon)

*   **SIP Protokolü Yönetimi:** `sentiric-sip-gateway-service`'e kayıt olma (`REGISTER`), çağrı başlatma (`INVITE`) ve çağrı alma işlemlerini yönetir.
*   **Medya Akışı (RTP/SRTP):** Cihazın mikrofonundan gelen ses akışını şifreleyerek platforma gönderir ve platformdan gelen ses akışını hoparlörde çalar.
*   **WebRTC Desteği (JavaScript için):** Tarayıcı tabanlı uygulamalar için WebRTC standardını kullanarak SIP iletişimini mümkün kılar.
*   **Geliştirici Dostu API:** `connect()`, `makeCall()`, `hangup()`, `onIncomingCall` gibi basit ve anlaşılır bir API sunarak entegrasyonu kolaylaştırır.

## 🛠️ Teknoloji Yığını (Planlanan)

*   **Web:** TypeScript, `JsSIP` veya benzeri bir WebRTC SIP kütüphanesi.
*   **iOS:** Swift
*   **Android:** Kotlin

## 🔌 API Etkileşimleri

*   **Protokol İletişimi:**
    *   `sentiric-sip-gateway-service`: SIP (sinyalleşme) ve RTP/SRTP (medya) için doğrudan iletişim kurar.

## 🤝 Katkıda Bulunma

Bu servis henüz geliştirme aşamasında olmasa da, fikirlerinizi ve önerilerinizi `sentiric-governance` reposunda bir `Issue` açarak paylaşabilirsiniz.

---
## 🏛️ Anayasal Konum

Bu servis, [Sentiric Anayasası'nın (v11.0)](https://github.com/sentiric/sentiric-governance/blob/main/docs/blueprint/Architecture-Overview.md) **Zeka & Orkestrasyon Katmanı**'nda yer alan merkezi bir bileşendir.