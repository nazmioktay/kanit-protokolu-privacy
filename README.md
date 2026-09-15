# Kanıt Protokolü — Gizlilik Politikası

Bu depo tek bir sayfa barındırır: **Kanıt Protokolü** Android uygulamasının
gizlilik politikası. Google Play, yayınlanan her uygulama için herkese açık
bir gizlilik politikası adresi zorunlu tutuyor.

**Yayın adresi:** https://nazmioktay.github.io/kanit-protokolu-privacy/

## Uygulama hakkında

Kanıt Protokolü, bilişsel davranışçı terapinin davranışsal deney fikrine
dayanan bir alışkanlık takip uygulaması. Tamamen çevrimdışı çalışır:
internet izni yoktur, hiçbir veri cihazdan dışarı çıkmaz.

## Sayfayı güncelleme

`index.html` elle düzenlenmez. Kaynak metin ana depodaki
`kanit_protokolu/store/privacy-policy-tr.md` dosyasında; HTML oradan
`build_privacy_html.py` ile üretilip buraya kopyalanır. Politika
değişirse önce markdown güncellenir, sonra sayfa yeniden üretilir ve
`Son güncelleme` tarihi değiştirilir.
