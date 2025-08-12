# 📱 Sentiric SIP Client SDK - Görev Listesi

Bu belge, `sip-client-sdk`'nın geliştirme yol haritasını ve önceliklerini tanımlar.

---

### Faz 1: Web (JavaScript/TypeScript) SDK'sı (Sıradaki Öncelik)

Bu faz, `sentiric-embeddable-voice-widget` ve `sentiric-web-agent-ui` gibi web tabanlı uygulamaların sesli iletişim kurabilmesi için temel SDK'yı oluşturmayı hedefler.

-   [ ] **Görev ID: SDK-SIP-001 - Proje Kurulumu ve Kütüphane Seçimi**
    -   **Açıklama:** TypeScript ve Rollup/Webpack kullanarak bir SDK projesi oluştur. WebRTC üzerinden SIP için en uygun kütüphaneyi (`JsSIP`, `sip.js` vb.) araştır ve seç.
    -   **Durum:** ⬜ Planlandı.

-   [ ] **Görev ID: SDK-SIP-002 - Bağlantı ve Kayıt (`Register`)**
    -   **Açıklama:** SDK'nın `sip-gateway`'e WebSocket üzerinden bağlanmasını ve bir kullanıcı adına `REGISTER` işlemi yapmasını sağlayan `connect()` metodunu implemente et.
    -   **Durum:** ⬜ Planlandı.

-   [ ] **Görev ID: SDK-SIP-003 - Çağrı Başlatma (`Invite`)**
    -   **Açıklama:** Belirtilen bir numaraya çağrı başlatan (`makeCall`) ve WebRTC `PeerConnection` üzerinden medya akışını başlatan mantığı implemente et.
    -   **Durum:** ⬜ Planlandı.

---

### Faz 2: Mobil (Native) SDK'lar

-   [ ] **Görev ID: SDK-SIP-004 - iOS SDK (Swift)**
    -   **Açıklama:** `sentiric-mobile` uygulaması için Swift dilinde bir SIP/RTP istemci kütüphanesi oluştur.
    -   **Durum:** ⬜ Planlandı.

-   [ ] **Görev ID: SDK-SIP-005 - Android SDK (Kotlin)**
    -   **Açıklama:** `sentiric-mobile` uygulaması için Kotlin dilinde bir SIP/RTP istemci kütüphanesi oluştur.
    -   **Durum:** ⬜ Planlandı.