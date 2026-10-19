# Scout Dosyası

Kişisel futbol scout defteri — maç notları, taktik formları, takip edilen takım/oyuncular.
Veriler API-Sports (API-Football) üzerinden gelir; notlar ve ayarlar Firebase (Firestore) ile cihazlar arası senkronlanır.

- Canlı adres: GitHub Pages (Settings → Pages → main / root)
- Telefona kurulum: adresi Safari'de aç → Paylaş → **Ana Ekrana Ekle**
- API anahtarı koda gömülü değildir; uygulamada Ayarlar'dan girilir (giriş yapınca buluttan gelir).
- `firestore.rules` içeriği Firebase Console → Firestore → Rules sekmesine yapıştırılmalıdır.
