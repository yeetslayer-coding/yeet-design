# Pinterest prompt kütüphanesi — ikinci güncelleme

13 Kasım 2026 · [skill panosu](https://tr.pinterest.com/lilyeet00/skill/)

## Kapsam ve doğrulama

- Canlı panoda **99 pin** görüldü; önceki 72 pinlik envantere göre **27 yeni pin** eklendi. Eski kayıtlar ve kimlikleri korunur; yeni numaralar P073–P099.
- Yeni pinlerden **62 görsel + 1 video = 63 kaynak kaydı** çıkarıldı. Her kayıt için ayrı, kaynak bağlantılı prompt vardır.
- P092’nin 10 slaytı önceki P054 ile birebir aynı dosyalardır (SHA-256 doğrulandı). Bunlar yeniden kayıt olarak tutuldu; bağımsız tercih kanıtı değildir. **52 yeni görsel ve 1 yeni video** vardır.
- Toplam Pinterest arşivi: **99 pin / 170 prompt kaydı**. İlk arşivin 107 kaydı korunur. Doğrudan kullanıcı yüklemeleri bu sayıya dahil değildir.
- Dört yeni karusel: P085 = 1 video + 15 görsel; P092 = 10 görsel; P095 = 4 görsel; P098 = 10 görsel. Diğer 23 yeni pin birer görsel içerir.
- Görseller ayrı ayrı görsel inceleme sayfalarında incelendi. Video 5,6 saniye; 0/2/4 saniye örnek kareleri incelendi, ses ve bütün geçiş zamanlamaları analiz edilmedi. Önceki 72 pinin slaytları bu güncellemede baştan incelenmedi.

[İlk 72 pin / 107 kayıt](../2026-11-13/index.md) · [Makine okunur kaynak envanteri](manifest.json) · [Doğrudan seçilmiş brand kit örnekleri](../../brandkit-delivery-2026-11-13/index.md)

## Bu eklemeden çıkarılan uygulanabilir ilişkiler

1. **Ana/ters renk sistemi:** P077 aynı ürün geometrisinde doğrudan zemin–logo değişimini gösterir. P080/P088/P094 kimliğin farklı uygulamalardaki karşılıklarıdır. YEET’in bütün paletlerde ve her üründe renk çifti kuralı geçerlidir.
2. **Aynı grafik, farklı görev:** P073/P078/P086’da tam logo, büyük motif ve küçük göğüs işareti farklı ölçeklerde kullanılır. Her yüzeye aynı büyüklükte logo yapıştırma.
3. **Çizim ailesi:** P087/P091/P093 ve P098-S10 çizgi ağırlığı, yüz, dolgu ve eylem sürekliliğini destekler. Maskot ancak brief’e uygunsa seçilir.
4. **Kimlikten malzemeye:** P085-S03/S04/S06 ve P090; metal, kâğıt, cam, kumaş ve temasın ayrı davranışını gösterir. Yalnız ışık efektine dayanarak gerçekçilik varsayma.
5. **Anlamdan grafik türetme:** P085-S05/S07/S09 isim, harf ve desenin kavramsal ilişkisini gösterir. Kaynağın kültürel hikâyesi başka markaya mal edilmez.
6. **Rehber + uygulama + bağlam:** P089 bilgi hiyerarşisi; P094 yakın/uzak ürün ritmi; P098-S02/S03/S06/S07 kullanım, detay ve reklam ölçekleri için seçilir. Yoğun kaynakları tek okunmaz post olarak taklit etme.

## Üretimde bağlayıcı kullanıcı kuralları

Prompt’lar tek kare rolü tarif etse de kullanıcı başka adet belirtmedikçe teslim **9–12 tamamlanmış ayrı post + bunlardan kolaj**dır. Varsayılan post ve kolaj 1080 × 1350 / 4:5; plan onayı üretimden önce alınır. Her markalı ürün ana ve ters zemin–logo düzeniyle set içinde görünür; gerçek ürün/ten/gıda renkleri ters çevrilmez. Palet swatch’larının üstünde **onaylı marka sembolü** yer alır; rastgele büyük harf değil. Bu kurallar her prompt’a eklenmiştir. Referans analizi kendi başına görsel üretim izni veya teslim değildir.

## Kayıt dizini

| Kayıt | Görsel karar / prompt | Tekrar |
|---|---|---|
| P073-S01 | [Orderside — modüler kurumsal ürün panosu](prompts/P073-S01.md) | — |
| P074-S01 | [Ocean Café — krem ambalaj ve mavi çizim](prompts/P074-S01.md) | — |
| P075-S01 | [Sayco — kobalt alanda siyah grafik kimlik](prompts/P075-S01.md) | — |
| P076-S01 | [Creative Agency — sarı yüzeyli promosyon ailesi](prompts/P076-S01.md) | — |
| P077-S01 | [Nori — birebir ters renk bardak çifti](prompts/P077-S01.md) | — |
| P078-S01 | [Gourmet Board Co — çizimli nötr ambalaj ailesi](prompts/P078-S01.md) | — |
| P079-S01 | [Burger House — ters renk bardak reklamı](prompts/P079-S01.md) | — |
| P080-S01 | [Corner Café — köşe hizalı tipografik envanter](prompts/P080-S01.md) | — |
| P081-S01 | [Beebee — ambalajlarda geometrik ikon ailesi](prompts/P081-S01.md) | — |
| P082-S01 | [Coffiyeh — dar kimlik envanteri kırpımı](prompts/P082-S01.md) | — |
| P083-S01 | [Coffiyeh — dikey envanterde ölçek dağılımı](prompts/P083-S01.md) | — |
| P084-S01 | [Brewist — bardaklarda yakın illüstrasyon kadrajı](prompts/P084-S01.md) | — |
| P085-S01 | [Coffiyeh — hareketli kimlik envanteri](prompts/P085-S01.md) | — |
| P085-S02 | [Coffiyeh — kapsamlı uygulama envanteri](prompts/P085-S02.md) | — |
| P085-S03 | [Coffiyeh — espresso makinesinde bardaklar](prompts/P085-S03.md) | — |
| P085-S04 | [Coffiyeh — kabartmalı kart ve sadakat sistemi](prompts/P085-S04.md) | — |
| P085-S05 | [Coffiyeh — harf ve motif yapım anlatısı](prompts/P085-S05.md) | — |
| P085-S06 | [Coffiyeh — çelik rafta beyaz bardak](prompts/P085-S06.md) | — |
| P085-S07 | [Coffiyeh — marka fikrinden tipografi türetme](prompts/P085-S07.md) | — |
| P085-S08 | [Coffiyeh — uygulama biçimli renk matrisi](prompts/P085-S08.md) | — |
| P085-S09 | [Coffiyeh — anlamdan türeyen dokuma deseni](prompts/P085-S09.md) | — |
| P085-S10 | [Coffiyeh — insan ve editoryal marka hikâyesi](prompts/P085-S10.md) | — |
| P085-S11 | [Coffiyeh — mekân fotoğrafında büyük logo](prompts/P085-S11.md) | — |
| P085-S12 | [Coffiyeh — metal tepside üstten servis](prompts/P085-S12.md) | — |
| P085-S13 | [Coffiyeh — editoryal kimlik açıklama sayfası](prompts/P085-S13.md) | — |
| P085-S14 | [Coffiyeh — sosyal postlarda tipografik ritim](prompts/P085-S14.md) | — |
| P085-S15 | [Coffiyeh — düz yüzey kimlik dağılımı](prompts/P085-S15.md) | — |
| P085-S16 | [Coffiyeh — kapanış sayfasında ambalaj ve açıklama](prompts/P085-S16.md) | — |
| P086-S01 | [Bluebeard — uzun dar harf ve servis karakteri](prompts/P086-S01.md) | — |
| P087-S01 | [After Brew — kartlarda maskot ve renk rolleri](prompts/P087-S01.md) | — |
| P088-S01 | [Mr. Waffle — maskottan araç ve üniformaya](prompts/P088-S01.md) | — |
| P089-S01 | [Mama — rehberden fiziksel uygulamaya kimlik şeması](prompts/P089-S01.md) | — |
| P090-S01 | [The Nook — sandalyede taşıyıcılı iki bardak](prompts/P090-S01.md) | — |
| P091-S01 | [Lama — üç kartta tek karakter sistemi](prompts/P091-S01.md) | — |
| P092-S01 | [SMASH 01 — çanta, bardak ve tepsi — yeniden kaydedilen pin](prompts/P092-S01.md) | P054-S01 |
| P092-S02 | [SMASH 02 — saplı kâğıt çanta — yeniden kaydedilen pin](prompts/P092-S02.md) | P054-S02 |
| P092-S03 | [SMASH 03 — patates üzerinde iki menü paneli — yeniden kaydedilen pin](prompts/P092-S03.md) | P054-S03 |
| P092-S04 | [SMASH 04 — açık burger kutusu ve bardak — yeniden kaydedilen pin](prompts/P092-S04.md) | P054-S04 |
| P092-S05 | [SMASH 05 — patates kutusu ve peçete — yeniden kaydedilen pin](prompts/P092-S05.md) | P054-S05 |
| P092-S06 | [SMASH 06 — lime A tabela — yeniden kaydedilen pin](prompts/P092-S06.md) | P054-S06 |
| P092-S07 | [SMASH 07 — kızarmış tavuk kovası — yeniden kaydedilen pin](prompts/P092-S07.md) | P054-S07 |
| P092-S08 | [SMASH 08 — elde okunan menü — yeniden kaydedilen pin](prompts/P092-S08.md) | P054-S08 |
| P092-S09 | [SMASH 09 — sekizli çizgi karakter ailesi — yeniden kaydedilen pin](prompts/P092-S09.md) | P054-S09 |
| P092-S10 | [SMASH 10 — restoran duvar uygulaması — yeniden kaydedilen pin](prompts/P092-S10.md) | P054-S10 |
| P093-S01 | [Plip — patlama biçimi ve yüz işareti](prompts/P093-S01.md) | — |
| P094-S01 | [Pawffle — sıcak fotoğraf ve kedi simgesi ailesi](prompts/P094-S01.md) | — |
| P095-S01 | [Nori Sushi — ön/arka kartta şef çizimi](prompts/P095-S01.md) | — |
| P095-S02 | [Pawlo — kartta sevimli maskot ve hizmet bağlamı](prompts/P095-S02.md) | — |
| P095-S03 | [Roamly — tipografik seyahat kartı](prompts/P095-S03.md) | — |
| P095-S04 | [Soleo — kartta ürün ve marka eşleşmesi](prompts/P095-S04.md) | — |
| P096-S01 | [Koko — kâğıt bantlı bardak yakın çekimi](prompts/P096-S01.md) | — |
| P097-S01 | [Talianis — mimari yüzeyde sakin tabela](prompts/P097-S01.md) | — |
| P098-S01 | [Cravea — kutularda sürekli çizgi ve karakter](prompts/P098-S01.md) | — |
| P098-S02 | [Cravea — insanın taşıdığı bardak ailesi](prompts/P098-S02.md) | — |
| P098-S03 | [Cravea — elde ürün ile yiyecek detayı eşleşmesi](prompts/P098-S03.md) | — |
| P098-S04 | [Cravea — saplı kutuda harf ölçeği](prompts/P098-S04.md) | — |
| P098-S05 | [Cravea — bardakta illüstrasyon ayrıntısı](prompts/P098-S05.md) | — |
| P098-S06 | [Cravea — servis anında paket ve makine](prompts/P098-S06.md) | — |
| P098-S07 | [Cravea — yan yana iki reklam yüzeyi](prompts/P098-S07.md) | — |
| P098-S08 | [Cravea — yoğun bardak tekrarında grafik ritim](prompts/P098-S08.md) | — |
| P098-S09 | [Cravea — çizimden dijitale süreç sunumu](prompts/P098-S09.md) | — |
| P098-S10 | [Cravea — tek çizim ailesinde farklı eylemler](prompts/P098-S10.md) | — |
| P099-S01 | [Brew Coffee — elde dört bardak, iki illüstrasyon](prompts/P099-S01.md) | — |
