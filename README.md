# Altıgen Kelime Oyunu — soru paketi

Bu depo, Android uygulamasının açılışta indirdiği **şifreli ve imzalı** soru paketini barındırır (GitHub Pages).

- `paket.txt` — sürüm, dosya adı, boyut, SHA-256 ve ECDSA imzası
- `paket-<sürüm>.bin` — AES-256-GCM ile şifrelenmiş soru paketi

Paketler yalnızca geliştiricinin bilgisayarındaki Soru Stüdyosu ile üretilir; imzası tutmayan paketi uygulama reddeder.
