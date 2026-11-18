# Portfolyo sitesi — kurulum

## 1. Düzenle
`index.html` dosyasını aç, en alttaki `<script>` içinde **CONFIG** bölümünü doldur:

- `githubUsername` → GitHub kullanıcı adın (repolar otomatik çekilir)
- `emails` → iletişim mailleri
- `fivemScripts` → kendi scriptlerinin adı, TR/EN açıklaması, etiketleri, varsa linki
- `nfts` → NFT görsellerini repoda `nft/` klasörüne yükle (Add file → Upload files, dosya adının başına `nft/` yaz), sonra `img: "dosya.png"` olarak gir
- `nftLinks` → NFT koleksiyonu ve X linkleri
- `aiCharacters` → karakter hesaplarının linkleri
- `socials` → LinkedIn, Instagram vb.

## Yayın
Site GitHub Pages ile https://yusufkaancelik.me adresinde yayınlanıyor. `main` dalına yapılan her değişiklik 1-2 dakikada siteye yansır.
