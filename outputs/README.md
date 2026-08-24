# ACA Dijital — Outputs Sistemi

Bu klasör, üretilmiş sosyal medya içerik paketlerinin düzenli arşividir.

## Klasör Yapısı

```text
outputs/
  YYYY-MM/
    week-01/
    week-02/
    week-03/
    week-04/
```

Örnek:

```text
outputs/2026-09/week-01/
```

## İçerik Dosya Adlandırma

Her içerik, aylık takvimdeki Content ID ile eşleşmelidir.

Örnekler:

```text
POST-001-reel.md
POST-002-carousel.md
POST-005-static-post.md
```

Görsel dosyalar varsa aynı ID ile adlandırılmalıdır:

```text
POST-001-reel-cover.png
POST-002-slide-01.png
POST-002-slide-02.png
POST-005-final.png
```

## Her İçerik Dosyasında Bulunması Gerekenler

- Content ID
- Tarih
- Format
- Kategori
- Hedef
- Hook / kapak başlığı
- Tam metin veya senaryo
- Sahne ya da slide yapısı
- Tasarım yönü
- Caption
- CTA
- Kullanılan kaynak / trend notu
- Durum
- Revizyon notları

## Durumlar

- `IDEA` — fikir hazır
- `COPY` — metin hazırlanıyor
- `DESIGN` — tasarım hazırlanıyor
- `REVIEW` — kontrol bekliyor
- `APPROVED` — yayınlanabilir
- `PUBLISHED` — yayınlandı

## Üretim Akışı

Her haftalık üretimde şu sıra izlenir:

1. `brand/brand-guide.md` oku.
2. `strategy/content-strategy.md` oku.
3. İlgili `calendar/YYYY-MM-content-calendar.md` dosyasını oku.
4. İlgili format için `templates/` şablonunu oku.
5. Daha önceki `outputs/` içeriklerini kontrol et.
6. Yeni içerikleri üret.
7. Her içeriği uygun haftanın klasörüne kaydet.
8. Revizyon geldikçe aynı içerik dosyasını güncelle.
9. Onay sonrası durumu `APPROVED` yap.
10. Yayınlandıktan sonra `PUBLISHED` olarak işaretle.

## Temel Kural

`calendar/` ne üretileceğini söyler.

`templates/` nasıl üretileceğini söyler.

`outputs/` ise gerçekten üretilen sonucu saklar.
