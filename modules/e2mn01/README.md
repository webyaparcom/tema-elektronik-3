# Menü E-Ticaret — `e2mn01` (tema-elektronik-3)

## Amaç
E-ticaret özel header navigasyon menüsü. Logo, kategori linkleri ve sepet ikonu ile alışveriş odaklı menü sunar. 2 farklı e-ticaret projesinde kullanılır. Sepet sayacı göstergesi, hover efektli renkler, koyu tema tasarımı ve sepet sayfasına yönlendirme URL entegrasyonu içerir. PLAN-PRO F3: giriş linki data-mx-uye-goster="misafir", Hesabım + Çıkış data-mx-uye-goster="giris" (MxStore.uye), sepet ikonunda data-mx-sepet-sayi rozeti (MxStore.sepet; 0 iken gizli).

## Meta
- version: `1.1.0`
- category: `menu`
- icon: `shopping_cart`

## Dosyalar
- `back.js` — sunucu tarafı çizim
- `index.html` — şablon
- `index.jpeg` — önizleme görseli
- `index.json` — tanım
- `README.md` — bu belge

## Not
Bu klasör siteye özel kurulum örneğidir; kurulum kaynağı `projeler/webyapar/data/tema/tema-set/icerik/elektronik-3/spec.js` → `tema-set/araclar/demo-kur.js` (webmaker uçları). Burası elle değiştirilmez; değişiklik spec'te yapılıp yeniden kurulur.
