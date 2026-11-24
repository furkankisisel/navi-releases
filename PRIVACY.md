# Navi Privacy Policy / Gizlilik Politikası

Last updated / Son güncelleme: 24 November 2026

Navi is a free Windows desktop application ("Dynamic Island" for your screen). This page explains what data Navi uses, especially when you connect your Google account.

---

## English

### Summary
- Navi has **no servers**. It does not collect, store, sell or share your data.
- Everything Navi reads from your Google account goes **directly between your computer and Google**. It is shown on your screen and nowhere else.
- You can disconnect your Google account at any time.

### Data Navi accesses when you sign in with Google
Navi asks for these Google permissions only after you choose "Connect with Google":

| Permission | What Navi uses it for |
|---|---|
| Email address (`openid`, `email`) | Showing which account is connected. |
| Gmail, read only (`gmail.readonly`) | Showing sender, subject and a short preview of new emails in the notch. Navi never sends, deletes or changes emails. |
| Google Calendar events (`calendar.events`) | Showing your upcoming events and adding an event when you type one in the quick-add box. |

### How the data is handled
- Emails and events are fetched on your computer, shown in the app, and kept only in the memory of the running app.
- The Google sign-in token (refresh token) is stored **only on your computer**, in encrypted form using Windows data protection.
- Navi does not transfer Google user data to the developer or to any third party, and does not use it for advertising or to train AI models.
- Navi's use and transfer of information received from Google APIs adheres to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements.

### Other features
Optional features (weather, prayer times, lyrics, Spotify, sports scores, update checks) contact their own public services directly from your computer, only when you turn them on. Navi does not send these requests through its own servers.

### Disconnecting and deleting data
- In Navi: Settings → Google → Disconnect. This deletes the stored token from your computer.
- You can also revoke access at any time at <https://myaccount.google.com/permissions>.
- Uninstalling Navi removes its local data.

### Contact
Questions: open an issue at <https://github.com/furkankisisel/navi-releases/issues>.

---

## Türkçe

### Özet
- Navi'nin **sunucusu yoktur**. Verilerini toplamaz, saklamaz, satmaz ve paylaşmaz.
- Google hesabından okunan her şey **doğrudan bilgisayarın ile Google arasında** gider. Yalnızca ekranında gösterilir.
- Google bağlantısını istediğin an kesebilirsin.

### Google ile bağlanınca eriştiği veriler
Navi bu izinleri yalnızca sen "Google ile bağlan"ı seçtikten sonra ister:

| İzin | Navi ne için kullanır |
|---|---|
| E-posta adresi (`openid`, `email`) | Hangi hesabın bağlı olduğunu göstermek. |
| Gmail, salt okunur (`gmail.readonly`) | Yeni e-postaların göndereni, konusu ve kısa önizlemesini çentikte göstermek. Navi e-posta göndermez, silmez, değiştirmez. |
| Google Takvim etkinlikleri (`calendar.events`) | Yaklaşan etkinliklerini göstermek ve hızlı ekleme kutusuna yazdığında etkinlik eklemek. |

### Veriler nasıl işlenir
- E-postalar ve etkinlikler senin bilgisayarında alınır, uygulamada gösterilir ve yalnızca çalışan uygulamanın belleğinde tutulur.
- Google oturum anahtarı (yenileme belirteci) **yalnızca senin bilgisayarında**, Windows veri koruması ile şifrelenmiş olarak saklanır.
- Navi, Google kullanıcı verilerini geliştiriciye veya üçüncü taraflara aktarmaz; reklam için ya da yapay zekâ modelleri eğitmek için kullanmaz.
- Navi'nin Google API'lerinden aldığı bilgileri kullanımı ve aktarımı, Sınırlı Kullanım gereklilikleri dahil [Google API Hizmetleri Kullanıcı Verileri Politikası](https://developers.google.com/terms/api-services-user-data-policy)'na uygundur.

### Diğer özellikler
İsteğe bağlı özellikler (hava durumu, namaz vakitleri, şarkı sözleri, Spotify, maç skorları, güncelleme kontrolü) yalnızca sen açınca, kendi herkese açık hizmetleriyle doğrudan bilgisayarından iletişim kurar. Navi bu istekleri kendi sunucularından geçirmez.

### Bağlantıyı kesme ve veri silme
- Navi'de: Ayarlar → Google → Bağlantıyı kes. Bu, saklanan anahtarı bilgisayarından siler.
- Erişimi istediğin zaman <https://myaccount.google.com/permissions> adresinden de kaldırabilirsin.
- Navi'yi kaldırmak yerel verilerini siler.

### İletişim
Sorular için: <https://github.com/furkankisisel/navi-releases/issues> adresinde konu aç.
