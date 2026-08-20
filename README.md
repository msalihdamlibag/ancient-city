# Anadolu Antik Kentleri — Gezi Sicili

Türkiye'deki antik kentleri kalıntının ayakta olma durumu, kazı ve sunum düzeyi,
tarihsel ağırlık ve ziyaret edilebilirliğe göre dört tabakaya ayıran tek dosyalık
gezi sicili. Ziyaret işaretleri tarayıcıda saklanır.

## Kullanım

`index.html` dosyasını tarayıcıda aç. Bağımlılık yok, derleme adımı yok —
tek bir statik HTML dosyası (CSS ve JS gömülü).

GitHub Pages ile yayınlamak için: Settings → Pages → Source olarak bu branch'i
ve kök dizini seç.

## İçerik

- **152 antik kent**, dört tabaka: S (20, Kaçırılmaz), A (52, Öncelikli), B (66, Yakınsan uğra), C (14, Tamamlayıcı)
- Kent/il araması, tabaka ve bölge filtreleri
- Ziyaret edilenleri işaretleme; ilerleme "kazı profili" olarak gösterilir
- Listeyi Markdown olarak panoya kopyalama
- Her kent için Google Haritalar bağlantısı

## Veri

Kent listesi `index.html` içindeki `D` dizisinde tutulur. Her satır:

```js
["Ad", "İl", "Bölge", "Tabaka", "Not"]
```

Yeni kent eklemek için diziye bir satır eklemek yeterli; kimlikler addan
otomatik üretilir.
