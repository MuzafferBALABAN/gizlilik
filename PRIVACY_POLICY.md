# Privacy Policy — Flag (`com.flag.journal`)

*(Türkçe metin aşağıdadır / English version first)*

---

## English — Privacy Policy

**Last Updated:** November 16, 2026

**Flag** ("the App", package ID `com.flag.journal`) is built to operate **100% offline** on your device.

1. **No Data Collection:** We do not operate servers, collect usage analytics, serve ads, embed tracking SDKs, or transmit any personal data, profiles, notes, or device identifiers off your device.
2. **Local-Only Storage:** All relationship aliases, flag logs, first impressions, and personal notes are stored exclusively in a local SQLite database on your device. Your optional 4-digit PIN is hashed with a cryptographic salt and stored inside your device's hardware-backed secure storage (Android Keystore / iOS Keychain).
3. **Encrypted Backups:** If you choose to export a `.flag` backup file, it is encrypted locally on your device using your chosen password with PBKDF2-HMAC-SHA256 (100,000 iterations) and AES-256-GCM. Your backup password is never stored or transmitted anywhere.
4. **Permissions:** The App requests only local biometric authentication (`USE_BIOMETRIC` / Face ID) when you enable app lock. It does not request contacts, location, camera, microphone, or background network permissions.
5. **Data Deletion:** Because all data resides solely on your device, you have full control and can delete individual profiles or permanently erase all data at any time by clearing app data or uninstalling the App.

---

## Türkçe — Gizlilik Politikası

**Son Güncelleme:** 16 Kasım 2026

**Flag** ("Uygulama", paket adı `com.flag.journal`), tamamen cihaz üzerinde (**%100 çevrimdışı**) çalışacak şekilde geliştirilmiştir.

1. **Veri Toplamama:** Uygulama hiçbir kişisel veriyi, profili, notu, kullanım istatistiğini veya cihaz tanımlayıcısını harici bir sunucuya göndermez, reklam veya izleme SDK'sı içermez ve üçüncü taraflarla paylaşmaz.
2. **Yerel Depolama:** Girdiğiniz takma adlar, bayrak kayıtları, ilk izlenimler ve notlar yalnızca kendi cihazınızdaki yerel SQLite veritabanında tutulur. İsteğe bağlı 4 haneli uygulama PIN'iniz cihazın güvenli donanım depolamasında (Android Keystore / iOS Keychain) tuzlanmış özet (hash) olarak saklanır.
3. **Şifreli Yedekleme Dosyaları:** Dışa aktardığınız `.flag` yedekleri, sizin belirlediğiniz parola kullanılarak cihazınızda PBKDF2-HMAC-SHA256 (100.000 tur) ve AES-256-GCM ile şifrelenir. Parolanız hiçbir yerde saklanmaz.
4. **İzinler:** Uygulama yalnızca kilidi açmak için cihazın yerel biyometrik kimlik doğrulama sistemini (`USE_BIOMETRIC` / Face ID) kullanır; konum, rehber, kamera, mikrofon veya arka plan ağ erişimi istemez.
5. **Veri Silme:** Tüm veriler yalnızca kendi cihazınızda bulunduğundan, uygulama içinden profilleri silebilir veya uygulamayı kaldırarak tüm yerel verileri kalıcı olarak silebilirsiniz.
