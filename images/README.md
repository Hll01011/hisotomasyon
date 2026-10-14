# HİS OTOMASYON — Fotoğraf ekleme rehberi

Site GitHub Pages üzerinde yayınlanır. Fotoğrafları yüklemek için kod yazman gerekmez.

## Fotoğraf yükleme

1. Bu depoda `images` klasörünü aç.
2. **Add file → Upload files** seç.
3. Bilgisayarından fotoğrafları seçip yükle.
4. Dosya adlarını aşağıdaki gibi yaz; boşluk ve Türkçe karakter kullanma.
5. **Commit changes** ile kaydet. Site birkaç dakika içinde güncellenir.

## Ana sayfa ve hizmet fotoğrafları

- `hero-pano.webp` — ana sayfadaki büyük pano fotoğrafı
- `kumes-otomasyonu.webp` — kümes otomasyonu
- `elektrik-panolari.webp` — elektrik panoları
- `plc-kontrol.webp` — PLC ve kontrol sistemleri
- `motor-yemleme.webp` — motor/yemleme ekipmanları

## Proje galerisi

Şu an ana sayfadaki uygulama galerisi için kullanılan fotoğraf dosyaları:

- `proje-01.webp`
- `proje-02.webp`
- `proje-03.webp`

Fotoğraflar aynı adla `images` klasörüne yüklendiğinde sayfada otomatik görünür. Kod düzenlemen gerekmez. Dosya henüz yüklenmediyse sayfa geçici temsili görsel gösterir. Aynı dosya adı varsa GitHub mevcut dosyayı değiştirmek isteyip istemediğini sorar.

## İpuçları

- Fotoğrafları WebP formatında yükle; dosya adının uzantısı `.webp` olmalı ve HTML'deki adla birebir eşleşmeli.
- Hizmet kartı görsellerinde yaklaşık 30–100 KB, büyük veya tıklanarak açılan görsellerde yaklaşık 100–250 KB hedefle. Bunlar hedef aralıklardır; okunabilirlik ve görüntü kalitesini kontrol et.
- Dosyayı yalnızca `.jpg` adından `.webp` adına çevirmek yetmez; gerçekten WebP formatına dönüştürülmüş olmalı.
- Yalnızca kendi çektiğin veya kullanma iznin olan fotoğrafları yayınla.
- Logo, depo kökündeki `logo.svg` dosyasıdır. İleride PNG istersen ayrıca `logo.png` yükleyebiliriz.
