# Foto Hafıza – iPhone (Sideloadly) paketi

1. GitHub'da yeni bir depo aç (özel olabilir).
2. Bu klasörü depoya gönder (gizli `.github` klasörü dahil, bu yüzden git kullan):
   git init && git add -A && git commit -m "ios" && git branch -M main
   git remote add origin https://github.com/KULLANICI/DEPO.git && git push -u origin main
3. GitHub → Actions → "Build iOS IPA" → Run workflow. ~10 dk sürer.
4. Bitince çalıştırmanın altındaki Artifacts'ten "FotoHafiza-ipa" indir, zip'i aç → FotoHafiza.ipa
5. Sideloadly'de IPA'yı sürükle, Apple ID'ni gir, iPhone bağlı → Start.
6. iPhone: Ayarlar → Gizlilik ve Güvenlik → Geliştirici Modu (açık olmalı, iOS 16+)
   ve Ayarlar → Genel → VPN ve Cihaz Yönetimi → Apple ID'ne güven.
7. Ücretsiz Apple ID ile uygulama 7 günde sona erer: Sideloadly ile yeniden yükle (kayıtlar korunur).
