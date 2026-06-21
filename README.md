# page-to-post-template

**JeoTurizm EduPanel — Blogger Post Şablonu**  
Akademik page sayfalarını hızlıca Blogger post formatına dönüştürmek için.

## Klasör Yapısı

```
page-to-post/
├── page-to-post-template.txt   ← Ana şablon (buradan kopyala)
├── examples/                   ← Gerçek post örnekleri
│   ├── post-vs30-soilclassification.html
│   └── post-seismologyengineering-global.html
├── exports/                    ← PDF/Word çıktıları için
└── README.md
```

## Kullanım

1. `page-to-post-template.txt` dosyasını kopyala, yeni isimle kaydet
2. `POST_BASLIGI`, `VIDEO_ID`, `POST_TARIH` gibi yer tutucuları doldur
3. Blogger > Yeni Yazı > HTML modu > yapıştır

## Sürüm Notu — v4.1 (Haziran 2026)

- `table-layout:fixed` — sütun genişlikleri stabil
- `td:first-child` → `width:140px`, `text-align:center`, `white-space:nowrap`
- `td` → `text-align:justify`, `hyphens:auto`, `vertical-align:middle`
- Tablo ikonu ve etiket artı ayrı `<div>` ile kırılmasız

## İlgili SeismoReport Sayfaları

| Post | Page (Tam Rapor) |
|------|-----------------|
| post-vs30-soilclassification.html | aliosmanoncel.blogspot.com/p/vs30-soilclassification.html |
| post-seismologyengineering-global.html | aliosmanoncel.blogspot.com/p/seismologyengineering-global.html |

## Yazar

Prof. Dr. Ali Osman Öncel  
İstanbul Üniversitesi–Cerrahpaşa, Jeofizik Mühendisliği  
ali.oncel@iuc.edu.tr
