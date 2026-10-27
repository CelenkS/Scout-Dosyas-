# Scout Dosyası

Kişisel futbol scout defteri — maç notları, taktik formları, takip edilen takım/oyuncular.
Veriler API-Sports (API-Football) üzerinden gelir; notlar ve ayarlar Firebase (Firestore) ile cihazlar arası senkronlanır.

Notlarım sekmesinde üçüncü bir alt sekme olarak **🎓 Gelişimim** var: teknik
direktörlüğe giden lisans basamaklarını (Temel Eğitim → UEFA C → B → A → Pro)
durumlarıyla (Henüz başlamadım / Planlıyorum / Devam ediyor / Tamamladım) ve
isteğe bağlı bir notla takip ediyor, altında da serbest "Hedef & Taktik
Notlarım" tiklenebilir listesi var. Güncel başvuru şartları/ücretleri
tff.org'dan kontrol edilmeli, oradan bir bağlantı da sekmenin içinde var.

- Canlı adres: GitHub Pages (Settings → Pages → main / root)
- Telefona kurulum: adresi Safari'de aç → Paylaş → **Ana Ekrana Ekle**
- API anahtarı koda gömülü değildir; uygulamada Ayarlar'dan girilir (giriş yapınca buluttan gelir).
- `firestore.rules` içeriği Firebase Console → Firestore → Rules sekmesine yapıştırılmalıdır.
