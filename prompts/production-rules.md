# ACA Dijital — AI Production Rules

Bu dosya ACA Dijital sosyal medya üretiminde tüm AI çalışmalarının ortak çalışma kurallarını tanımlar.

## Zorunlu Okuma Sırası

Her üretimde önce:

1. `brand/brand-guide.md`
2. `strategy/content-strategy.md`
3. İlgili `calendar/YYYY-MM-content-calendar.md`
4. İlgili `templates/` dosyası
5. Önceki ilgili `outputs/` içerikleri

okunmalıdır.

## Üretim İlkeleri

- Marka kimliğine sadık kal.
- İçerikleri birbirinin kopyası gibi üretme.
- Her içerikte net bir iş hedefi olsun.
- Hook güçlü ve kısa olsun.
- Tasarım açıklaması soyut değil somut olsun.
- Araçlar izin veriyorsa görseller gerçekten üretilecek şekilde hazırlanmalı.
- Reel için sadece fikir değil; senaryo, storyboard, cover ve sahne yönleri hazırlanmalı.
- Carousel için tüm slide metinleri ve tasarım sistemi hazırlanmalı.
- Static post için final kompozisyon açıkça tanımlanmalı.
- Güncel trend içeriği üretirken gerektiğinde web araştırması yap.
- Doğrulanmamış sayısal iddialar kullanma.

## ACA Görsel Kontrolü

Ana görsel karakter:

- premium
- modern
- editorial
- high contrast
- siyah / beyaz temel
- kontrollü ACA turuncusu
- güçlü tipografi
- temiz negatif alan
- profesyonel kreatif ajans hissi

Kaçınılacak:

- hazır Canva şablonu hissi
- aşırı gradient
- çok fazla renk
- klişe stock görsel
- çocukça ikonografi
- aşırı dekorasyon
- okunamayacak kadar küçük metin

## Dosyalama Kuralı

Üretilen içerik şu yapıda kaydedilmelidir:

`outputs/YYYY-MM/week-XX/POST-XXX-format.md`

Örnek:

`outputs/2026-09/week-01/POST-001-reel.md`

Üretilen somut tasarım dosyaları ayrıca:

`outputs/YYYY-MM/week-XX/designs/`

altında tutulmalıdır.

Her tasarım için mümkünse hem kaynak/vektör dosyası hem de Canva Magic Layers için kullanılabilecek PNG önizleme üretilmelidir.

## Canva Senkron Kuralı

Her yeni somut tasarım oluşturulduğunda GitHub kaydı ile aynı üretim akışında Canva'ya da aktarılmalıdır.

Canva klasör yapısı:

`ACA / <Ay Adı> <YYYY> İçerikleri`

Örnek:

`ACA / Eylül 2026 İçerikleri`

Kurallar:

- Her `POST-XXX` tasarımı Canva'da ayrı bir design olmalıdır; birden fazla post tek kolaj veya tek sayfada birleştirilmemelidir.
- Reel cover, carousel cover/slide ve static post ayrı tasarım dosyaları olarak tutulmalıdır.
- Tasarım PNG/JPEG gibi düz görselse Canva Magic Layers / image-to-design kullanılarak mümkün olduğunca düzenlenebilir katmanlara ayrılmalıdır.
- Canva tasarım başlığı `POST-XXX — Format — Kısa Konu` biçiminde olmalıdır.
- Aynı başlık veya aynı POST için Canva'da mevcut tasarım varsa gereksiz kopya oluşturma; mevcut tasarımı kontrol et.
- İlgili ay klasörü yoksa `ACA` altında otomatik oluştur.
- Canva bağlantısı geçici olarak kullanılamıyorsa GitHub üretimini durdurma; eksik Canva senkronunu sonraki çalışmada tamamla.

## Revizyon Kuralı

Kullanıcı revizyon istediğinde yeni bağımsız içerik oluşturmak yerine mevcut POST dosyası güncellenmelidir.

Revizyon notu dosyanın altında tutulmalıdır.

## Onay Kuralı

Durum akışı:

`IDEA → COPY → DESIGN → REVIEW → APPROVED → PUBLISHED`

Kullanıcı açıkça onaylamadan içerik `APPROVED` sayılmamalıdır.
