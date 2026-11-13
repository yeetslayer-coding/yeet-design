---
name: yeet-design
description: Yiğit Akalın için brief'e göre marka kimliği, ambalaj ve sosyal medya/reklam görselleri planla, üret ve revize et. Kullanıcının Behance işleri, Pinterest panoları ve doğrudan geri bildirimlerinden yararlan; yeni referans panolarını inceleyerek bu kişisel tasarım bilgisini güncelle. YEET tasarım skill'i, kullanıcının estetiğine uygun reklam veya referanslardan branding öğrenme istendiğinde kullan. Genel web arayüzü işleri için otomatik uygulama.
---

# YEET Design

Bu skill tek bir görsel stil dayatmaz. Kullanıcının isteğine göre tasarım kararları verir. Kullanıcıya Türkçe, doğrudan ve somut kararlarla yanıt ver. **Her çağrıda önce planla; tasarım üretimini plan onayından sonra yap. Adet belirtilmediyse varsayılan teslim 9–12 ayrı post ve bunları birleştiren kolajdır; tek postla bitirme. Her ürün/markalı uygulama için ana ve zemin–logo renkleri yer değiştirmiş ikinci versiyonu dahil et. Boyut belirtilmediyse her postu ve teslim kolajını 4:5, 1080 × 1350 px hedefiyle hazırla.**

## Kaynakları kullanma sırası

1. Güncel brief ve kullanıcının açık düzeltmeleri.
2. İşin mevcut marka dosyaları ve doğrulanmış ürün bilgisi.
3. Bu işe uyan referanslar ve bunlardan çıkarılmış, henüz kullanıcı tarafından tek tek onaylanmamış estetik yorumlar.

Behance ile Pinterest arasında sabit bir ağırlık kurma. Panoya kaydedilen her öğeyi bütünüyle beğenilmiş sayma. Bir işteki paleti, maskotu, fontu veya efekt yoğunluğunu diğer işe zorunlu taşıma. Yeni brief önceki işin adını, renklerini veya ürününü miras almaz.

İlk kullanımda [kullanıcı kararlarını](references/user-decisions.md) oku. Kaynak seçerken [referans geçmişine](references/reference-history.md) ve gerektiğinde [branding panosu incelemesine](references/branding-board-2026-11-13.md) başvur. Tüm arşivi her üretimde yeniden açma.

**Tek tek görsel prompt’ları:** [Son eklenen 27 pin / 63 kaynak kaydının prompt dizini](references/prompt-library/2026-11-13-update-02/index.md) ile [ilk 72 pin / 107 kayıt](references/prompt-library/2026-11-13/index.md) birlikte **99 pin / 170 prompt kaydını** kapsar. Son ekleme 62 görsel ve 1 videodur; 10 görsel önceki SMASH serisinin birebir tekrarıdır. Referansla tasarım veya benzer kompozisyon istendiğinde brief’e uyan kayıtları bu dizinlerden seç; seçilen prompt’u ve bağlı kaynak görseli aç. Her kayıt kompozisyonu, harf/grafik davranışını, renk rollerini, ilgili ışık/malzeme kararını ve uyarlama sınırını taşır. Köşeli brief değişkenlerini gerçek iş bilgisiyle doldur; kaynak marka, fiyat ve iddiaları yeni ürüne aktarma. Tekrar kayıtlarını bağımsız tercih kanıtı sayma; bütün katalogu her işe yükleme. Kütüphanedeki prompt’un varlığı yeni görsel üretimi için plan onayının yerine geçmez.

Kullanıcının kalite hedefi olarak özellikle yeniden gönderdiği referansları, genel Pinterest kayıtlarından daha güçlü iş yönlendirmesi say. Son saat kitinin reddi ve dört seçilmiş örnek [editoryal referans incelemesinde](references/2026-11-13-editorial/analysis.md) kayıtlıdır. Ürün fotoğrafı içeren işte [gerçekçilik ve tipografi iş akışını](references/product-photography-and-type.md) oku.

**Brand kit istendiğinde**, kullanıcının doğrudan teslim örneği olarak seçtiği [Taste Mood ve dört maskotlu marka sistemi kaydını](references/brandkit-delivery-2026-11-13/index.md) oku; ilgili prompt ve kaynak görseli aç. Bunlar Pinterest envanterinden ayrı iki kullanıcı yüklemesidir ve beş marka sistemi içerir. Beklenti: ana logo → gerekli varyasyonlar → renk/tipografi → ilgili uygulamalar → varsa yardımcı grafik/desen ilişkisini gösteren kimlik sunumu. Planına bu sunumu dahil et; yalnız ürün reklamlarını yan yana dizerek tam brand kit teslim edildiğini varsayma. Kırmızı palet, retro gıda dili veya maskot zorunluluğu çıkarma; uygulama türü ve sayfa adedi güncel brief’e göre belirlensin.

## Zorunlu plan ve onay akışı

Kullanıcı bu skill'in her kullanımda Plan moduyla başlamasını açıkça istiyor. Bu kural yeni tasarım, revizyon, font değişikliği ve brand kit taleplerini kapsar. “Tasarla”, “üret” veya “değiştir” sözcüklerini, henüz sunulmamış bir tasarım planının onayı sayma.

1. Önce brief'i ve mevcut referansları incele. Somut tasarım kararlarını, çıktı listesini/adedi ve her çıktının boyutunu içeren kısa, incelenebilir bir plan sun.
2. Yeni veya değişen tasarım planı kullanıcı tarafından onaylanmadan imagegen veya başka bir üretim/düzenleme aracıyla teslim görseli oluşturma. Referans inceleme, dosya okuma ve plan hazırlama yapılabilir. Kullanıcının doğrudan istediği skill kuralı düzenlemesi için ayrıca tasarım onayı gerekmez.
3. Kullanıcı sunulmuş planı onayladığında veya o plan için “uygula/üret” dediğinde yeniden onay isteme; onaylanan kapsamı tamamla. Küçük uygulama tercihlerini yeni onay kapısına dönüştürme. Kullanıcı o iş için açıkça plan aşamasını atlamanı isterse güncel talimatı uygula.

**Gerçek uygulama modu ile plan davranışını ayır:** Skill metni ve `agents/openai.yaml` kendi başına Codex'in gerçek `/plan` modunu değiştiren bir mekanizma değildir. Oturum gerçek Plan modundaysa onun kısıtlarına uy. Ortam resmî bir mod değiştirme aracı sağlıyorsa kullan ve sonucunu doğrula. Böyle bir araç yoksa gerçek modun açıldığını söyleme; kullanıcıya bunu kısaca belirt ve yukarıdaki önce-plan/onay akışını yine uygula. Uydurma `mode: plan` metadata'sı, gizli uygulama ayarı veya zamanlanmış otomasyon ekleme.

Yalnız referans analizi/skill bakımı istenmişse inceleme planını kısaca belirtip yetkili inceleme/düzenleme işini tamamla; ortada görsel üretimi yokken gereksiz bir tasarım onayı isteme.

Brief'ten ürünü, hedef kitleyi, ana mesajı, formatı, istenen adedi, zorunlu yazıları, mevcut kimliği ve yasakları çıkar. Sonucu belirgin değiştirecek eksik bilgi için kısa soru sor; kalan işi sürdür. Hayalî işte geri alınabilir seçimleri varsayım olarak belirt. Gerçek ürünün adını, içeriğini, fiyatını, sertifikasını veya performans iddiasını uydurma.

Planı yalnız “premium, dinamik, bold, sinematik” gibi sıfatlarla kurma. Aşağıdaki kararları brief'in gerektirdiği ölçüde somutlaştır:

| Karar | Planın açıklaması gereken şey |
|---|---|
| Marka fikri | Bu markanın nasıl bir karakter taşıdığı ve neden bu ürün/insanlarla ilişkili olduğu. |
| Marka yazısı | Harf oranı, iç boşluk, ritim, bağlantı veya ayırt edici hareket; mevcut logo varsa onu koruma biçimi. |
| Tipografi görevleri | Marka adı, kategori/ürün adı, ana mesaj ve küçük bilginin okuma sırası. Bir font farklı görevleri üstlenebilir. |
| Renk görevleri | Hangi renk geniş yüzeyi, hangisi yazıyı, vurguyu veya ürün ayrımını taşıyor. Palet listesi tek başına yeterli değil. |
| Grafik dil | Varsa harften, üründen veya fikirden türeyen işaret, desen, çerçeve ya da illüstrasyon; kompozisyonla ilişkisi. |
| Ambalaj/sayfa düzeni | Bilgi ölçekleri, hizalar, boşluk ve görünür yüzeylerin görevleri. |
| Sahne | Kimliği destekleyen kadraj, ürün ölçeği, malzeme, ışık, derinlik ve hareket. |

Planın referans bağlantısını somutlaştır: seçilmiş her ilgili örnek için **görülen karar → bu işte uygulanacak karşılığı → uygulamanın görüneceği kare/yüzey** yaz. Yalnız palet/font adı veya “ultra realistic, premium, elegant” sıfatlarıyla üretim planını tamamlanmış sayma. Kullanıcının reddettiği yönü küçük kozmetik değişiklikle yeniden üretme.

Her iş için yeni bir logo çizmek, maskot eklemek, iki font kullanmak veya bütün tabloyu kullanıcıya göstermek zorunlu değil. Yalnız tipografi, oran, boşluk ve renk dağılımıyla da belirgin kimlik kurulabilir. “Markaya ait bir dil” koşulunu rastgele dekorasyonla doldurma.

Kullanıcının güncel brief’te açıkça belirttiği adet önceliklidir; açık tek-görsel talebini kendiliğinden büyütme. **Adet belirtilmemiş tasarım/branding işini tek görsel olarak yorumlama: 9–12 post ve kolaj varsayılanını uygula.** Kullanıcı birden fazla yaratıcı yön isterse fikir, tipografi veya düzen bakımından farklı yönler kur; ana/ters renk versiyonlarını ayrı yaratıcı yönler diye sayma.

## Varsayılan seri, kolaj ve zorunlu renk çiftleri

- **Adet ve plan:** Yeni görsel üretimi için adet belirtilmediyse 9 post planla; tüm ürünlerin ana/ters renkleri ve kimlik/uygulama/çekim çeşitliliği 9’a okunur biçimde sığmıyorsa 12 post planla. Bu ikisi kullanıcının 9–12 aralığındaki düzen varsayılanlarıdır; açıkça istenen 10/11 veya başka adet önceliklidir. Plan her postun görevini, gösterdiği ürünleri ve renk versiyonunu listelesin. 9–12 toplamı ana ve ters versiyonları birlikte kapsar; 9 temel postu sessizce 18’e çıkarma. Gerektiğinde aynı postta karşılaştırılabilir bir renk çifti göster; yalnız sayıyı doldurmak için kare çoğaltma.
- **Her üründe iki uygulama:** Bardak, kutu, çanta, kart, tabela, tekstil, cihaz/kılıf ve projede tasarlanan diğer markalı yüzeylerin her biri ana ve ters renk düzeniyle gösterilsin. Kural bütün marka paletleri için geçerlidir; kırmızı veya beyaz zorunlu renk değildir. Genel eşleşme: **A renkli yüzey + B renkli logo ↔ B renkli yüzey + A renkli logo**. Örnekler: mavi/beyaz ↔ beyaz/mavi; siyah/krem ↔ krem/siyah; yeşil/sarı ↔ sarı/yeşil. Renk çiftini güncel markanın onaylı paletinden al. Sadece logo sunumunda ters versiyon göstermek ürün çiftlerinin yerine geçmez. Aynı ürün farklı fotoğraflarda tekrar ediyorsa her sahneyi ikiye katlamak gerekmez; teslim setinde o ürünün iki versiyonu açıkça bulunmalı.
- **Ters renk tanımı:** Onaylı paletin ana zemin ve logo/ön plan renkleri yer değiştirir. Bu, renk çemberindeki tamamlayıcı rengi seçmek veya tüm fotoğrafa negatif/RGB invert filtresi uygulamak değildir. Çok renkli kimlikte değişen ana renk çiftini ve sabit kalan yardımcı renkleri planda belirt. Gerçek ürünün gıda içeriği, insan teni, cam şeffaflığı, lensleri, metal yansımaları ve çevre ışığı ters çevrilmez; markalı yüzeyin rengi değişir.
- **Aynı kimliği koru:** Eşleşen iki versiyonda ürün geometrisi, logo çizimi, metin, baskı ölçeği ve yerleşim aynı olsun. Karşılaştırma karesinde açı/ışık/malzeme tutarlı kalsın. Ters versiyonu ilk ürün kaynağına dayalı düzenleme olarak üret; yeni bir logo/ürün tasarımına dönüştürme. Yüzey rengine göre yansıma ve kısa temas gölgesi doğal biçimde uyarlansın, okunurluk iki versiyonda da kontrol edilsin.
- **Kolaj teslimi:** Her post gerçek, tamamlanmış ayrı dosya olarak üretilsin. Sonunda bunlardan bir toplu kolaj oluştur ve sohbet içinde ana sonuç olarak göster; yalnız tek post veya ZIP bağlantısıyla bitirme. Dokuz postta 3×3, on iki postta 3×4 düzen kullan; diğer adetlerde üç sütunlu düzeni temiz biçimde tamamla. Postların oranını koru; sığdırmak için esnetme veya önemli içeriği kesme. Kolajın kenar boşluklarını post oranlarına göre ayarla. Tekil dosyalar ve prompt’lar da teslim paketinde bulunsun. Kolaj, post sayısına dahil ek bir içerik postu değildir.

Bu kurallar yeni tasarım üretimi içindir; yalnız referans inceleme veya skill güncellemesi istendiğinde kendiliğinden 9–12 görsel üretme. Ayrıntılı brand kit prompt eki ve teslim kontrolü [burada](references/brandkit-delivery-2026-11-13/index.md).

## Varsayılan Instagram formatı

- Kullanıcı ölçü veya kullanım formatı belirtmediyse **her yeni teslim görseli 4:5 dikey Instagram postu; hedef dosya 1080 × 1350 px**. Reklam, marka kiti genel görünümü, logo sunumu ve serinin her sayfası bu varsayılana dahildir.
- Kullanıcının açıkça istediği farklı ölçü/oran ya da story, yatay banner gibi farklı format önceliklidir. Referans görselin yatay olması tek başına farklı çıktı boyutu talimatı değildir.
- Birlikte kullanılan başka bir skill'in 4:3, 16:10 veya yatay marka panosu varsayılanı bu kullanıcı kuralını geçersiz kılamaz. Yoğun brand kit içeriğini okunmaz biçimde tek posta sıkıştırma; gerekiyorsa plan aşamasında 4:5 sayfalardan oluşan bir carousel öner ve adedini onaya sun.
- Kompozisyonu baştan dikey kur. Onaylı 4:5 kompozisyonu sonradan esnetme veya önemli öğeleri kesen otomatik kırpmayla uydurma.
- Üretim prompt'unda hedef boyutu belirt; gerçek dosya ölçüsünü teslimden önce oku. Gerekli teknik dışa aktarımı mevcut araçların kurallarına uyarak yap. Araç hedef pikseli sağlayamıyorsa gerçek ölçüyü bildir; yaklaşık oranı veya farklı çözünürlüğü 1080 × 1350 diye sunma.
- Kullanıcının kaynak görsellerini bu varsayılan nedeniyle değiştirme. Kural üretilecek teslim görsellerinin formatıdır.

## Marka kimliğini sahneye taşı

- Yeni markada önce ambalajın düz ön yüzünü düşün: marka, ürün/kategori ve bilgi düzeni kendi başına karakter taşıyor mu? Büyük 3D arka plan yazısı bunu tek başına sağlamaz.
- Kelimenin siluetini ve harf ilişkilerini tarif et. “YEET yazan kalın eğik font” ayırt edici bir karar sayılmaz. Mevcut markayı izinsiz yeniden tasarlama.
- Yardımcı grafik kullanıldığında kaynağı ve görevi açıklanabilsin. Harf eğrisi → yüzey bölünmesi; kategori işareti → küçük desen; marka fikri → illüstrasyon ailesi gibi ilişkiler kur. Referansın logosunu veya maskotunu yeni markaya kopyalama.
- Birden fazla yüzey/format varsa hepsine aynı büyüklükte logo yapıştırma. Örneğin bir yüzey marka adını, diğeri simgeyi, küçük etiket kısa bilgiyi taşıyabilir. İşin gerektirmediği yüzeyleri üretme.
- Tutarlılık, aynı kompozisyonu tekrarlamak değildir. Sabit kalan harf karakterini, renk rollerini ve grafik davranışı koru; ölçek, yön, kadraj ve bilgi yoğunluğunu uygulamaya göre değiştir.
- İllüstrasyon ailesi varsa çizgi ağırlığı, uçlar, yüz ifadeleri, dolgu oranı ve biçim dili birbiriyle uyuşsun. Maskot zorunlu değil.
- Ambalaj, reklam yazısı ve çevre aynı fikri desteklesin. İçerik/ürün çağrışımı olan nesneler kullan; anlamı olmayan parçacık, meyve, sıvı veya rozet ekleme.
- Fotogerçekçi, düz grafik, editoryal, retro, sade veya yoğun yönü brief belirlesin. Koyu sahne, merkezde ürün, grain, krom, dev yazı ve güçlü kontrast varsayılan reçete değildir.

## Seçilmiş referansların uygulama disiplini

- Brand kit'in kapsamı logo ve renk örnekleriyle sınırlı kalmasın: ürün, kullanım bağlamı, fiziksel yüzey ve detayda aynı kimliğin nasıl davrandığını göster. Gerekli sayfa adedini planda belirle; her kit için sabit dokuzlu grid dayatma.
- Kimlik sunumunda ana logo, anlamlı kullanım varyasyonları ve okunur renk/tipografi bilgisi yer alsın. Uygulamalar arasında tam logo, küçük işaret, mesaj ve varsa desen farklı görevler üstlensin. Maskotlu sistemde ana poz, alternatif eylem, baş kırpımı ve mühür aynı karakter çiziminden türesin; yüz, kıyafet, oran ve çizgi ağırlığı değişmesin. Örneklerin tüm aksesuarlarını her markaya ekleme; yoğun bilgiyi okunmaz küçültmek yerine sayfa kapsamını planda çöz.
- **Palet üstünde marka sembolü:** Brand kit’in renk paletiyle birlikte gösterilen kimlik panelinde, swatch’ların üstündeki büyük odak markanın mevcut/onaylı ana sembolü veya amblemi olsun. Kelime markasından rastgele büyütülmüş bir harfi bu alana koyma. Aroma örneğinde büyük “a” yerine taç kullanılır; başka markaya taç taşınmaz. Harf ancak markanın onaylı sembolü/monogramı ise bu rolü üstlenebilir. Marka sembolü yoksa yeni kimlik planında bu ihtiyacı çöz; mevcut markaya izinsiz işaret icat etme. Bu kural ambalajda veya ayrı tipografi sayfasında büyük harf kullanımını yasaklamaz.
- Kimlik panosunda ve seri planında her ürünün ana/ters renk uygulamasının hangi postta göründüğünü eşleştir. İkili renk uygulamalarının yanında kimlik bilgisi, kullanım bağlamı ve detay çeşitliliğini de koru; bütün seriyi tek mockup’ın renk değişimleriyle doldurma.
- Ürünlü bir seride **genel/bağlam, orta/ana ürün, yakın/makro detay** farklı bilgi taşısın. Tek packshot'ı büyütüp küçültmeyi ayrı çekim fikri sayma. Tek post istenirse bu çekimlerden brief'e en uygun olanı seç; otomatik seri üretme.
- Renk uyumunu yalnız hex listesiyle ölçme. Renklerin kapladığı alanı, açık-koyu kütleleri, sıcak-soğuk ilişkisini ve doygunluk dağılımını sahneler arasında dengele. Kullanıcının simetri talebini optik dengeyle çöz; bütün sahneleri zorunlu merkezleme/aynalama şeklinde yorumlama.
- İstenen ürün fotoğrafı tamamen gerçekçi görünmeli. Kullanıcının istediği **Sony Alpha 7 IV + Sony FE 90mm f/2.8 Macro G OSS** görünümünü çekim tarifine dahil et; mesafe, odak düzlemi, ışık kaynağı ve malzeme davranışını da somutlaştır. Kamera adını yazmayı gerçekçilik kanıtı sayma; yapay üretimi bu kamerayla gerçekten çekilmiş diye sunma.
- **Güzellik filtresi kullanma.** Doğal ten dokusunu, görünür ince tüy/saçları ve gerçek kumaş/zemin davranışını koru; ağır rötuş, cilt yumuşatma, plastikleştirme ve yapay parlatma uygulama. Kullanıcının bu saat serisine son yönlendirmesi: kapalı sabah ışığı, 35 mm görünümü, hafif film dokusu ve yıpranmış ahşap. Güncel sahne yönü önceki güneşli/90 mm yaşam sahnesi tarifinden önceliklidir; ürün makrosunda 90 mm yönü korunabilir.
- Ürünün gerçekliği için kaynak fotoğraftaki kasa/gövde kalınlığını, düğme sayısı ve yerini, bağlantıları ve malzeme oranlarını karşılaştır. Ürün kaymışsa yalnız ışığı değiştirerek veya daha küçük göstererek gizleme; ürün referansına dayalı düzeltme yap.
- Logo için tek bir doğrulanabilir ana çizim/dizgi kaynağı kullan. Gerekirse özel YEET harfleri çiz; dört harfli wordmark'ı tam font ailesi geliştirilmiş gibi sunma. Her sahnede modelin harfleri yeniden yorumlamasına dayanma.
- Yazılar ve küçük detaylar kalite hedefinin parçasıdır. Logo, harf aralıkları, Türkçe işaretler, görünür etiketler ve kadran rakamları tam boyda incelensin; bozuk küçük yazıyı “AI detayı” diyerek geçirme. Metin doğruluğu yöntemini planda belirt.
- Referanstaki gerçeklik hissi, ölçülü malzeme farkı ve doğal ışık davranışından gelir. Rasgele çizik/grain, aşırı bokeh veya kusur eklemek otomatik gerçekçilik çözümü değildir. Ekran görüntüsündeki uygulama düğmeleri, filigranlar ve gezinme metinleri tasarım diline dahil edilmez.

## Görsel üretimi ve revizyon

Raster üretim veya düzenleme gerektiğinde mevcut `imagegen` skill'ini ve ilgili görsel aracını kullan. Prompt'un başına marka fikrini, harf/düzen kararlarını ve metinleri koy; kamera ve ışık ayrıntıları bunları izlesin. Kullanıcı görsel üretimi istemediyse yalnız referans analizi sırasında yeni reklam üretme.

İstenen çıktı sayısına uy; sayı belirtilmemişse 9–12 post + kolaj ve her üründe ana/ters renk kurallarını uygula. Formatı ve gerçek çıktı ölçüsünü kontrol et; yaklaşık oranı kesin piksel teslimi diye sunma. Her postu ve kolajı görsel olarak açıp incele. Tekil görselleri, kolajı ve kullanılan prompt’ları çalışma alanında sakla; kolajı sohbet içinde göster ve tekil dosyalara erişim ver. Üretim hatası veya erişim engelini açıkça bildir.

Kullanıcı “ışık iyi, branding kötü” dediğinde ışık kalitesini koruyup marka yazısı, ambalaj hiyerarşisi ve grafik ilişkiyi değiştir. Aynı ambalaja daha fazla efekt eklemek revizyonun hedefini karşılamaz. Kullanıcı eleştirisini gözlenen problem ve uygulanacak karar olarak kaydet; tamamlanmış öğrenme veya model eğitimi iddiasında bulunma.

## Teslim öncesi üç ayrı değerlendirme

**Kimlik:** Ambalajın/ana grafiğin efektlerden bağımsız tanımlanabilen karakteri var mı? Marka yazısı, düzen ve varsa yardımcı biçimler ilişkili mi? Referans kullanıldıysa hangi yapısal ilke uygulandı? “Güzel görünüyor” yeterli kanıt değil. Mevcut sade bir markayı sırf daha ayırt edici yapmak için değiştirme.

Referansla yan yana karşılaştır: kadraj ölçeği/çeşidi, renk alan dengesi, tipografi ile fotoğrafın ilişkisi ve kimliğin yüzeye uygulanması için görünür karşılık göster. “Büyük hata yok” değerlendirmesi referans seviyesinde bir sonuç üretildiği anlamına gelmez.

**Brief ve doğruluk:** Metinler harf harf doğru mu, Türkçe karakterler korunmuş mu, yazı/zemin kontrastı gereken bilgiyi okunur kılıyor mu? İstenen renk, sayı, format ve mesaj sağlanmış mı? Uydurulmuş ürün iddiası, fiyat, sertifika veya anlamsız küçük yazı var mı?

**Seri kapsamı:** Açık farklı adet talebi yoksa 9–12 tamamlanmış tekil post ve bunlardan oluşturulmuş kolaj var mı? Tasarlanan her ürün/uygulama için ana ve ters zemin–logo renkleri gerçekten gösterilmiş mi? Dosya/adet veya küçük logo varyasyonlarını sayarak eksik ürün çiftini gizleme.

**Görsel uygulama:** Malzeme, ışık yönü, temas gölgesi, perspektif, baskının yüzeye oturması, kesimler, örtüşmeler ve istenen odak tutarlı mı? Tipografi yüzeyde bozuluyor mu?

Ürünlü seride malzeme ve mekanik geometri bütün karelerde aynı mı? Logo ve küçük yazı kaynağı tutarlı mı? Bir yakın çekimde görünür hale gelen hata, küçük önizlemede gizlenmiş olsa da düzeltilmeli. Bir kareyi inceleyip bütün seriye görsel onay verme.

Bu üç sonuç birbirinin yerine geçmez. İyi ışık/gölge, zayıf kimliği geçerli saydırmaz. Yalnız teknik kontrolü geçen bir işi kullanıcının estetik onayını almış gibi sunma. Belirgin kusuru düzelt; zevk açısından belirsizliği kesin başarı diye etiketleme.

## Pinterest / Behance güncelleme döngüsü

Kullanıcı yeni link gönderdiğinde mevcut kaydı kontrol et. Son gözlemde pano **99 pin** içerir: [ikinci güncelleme](references/prompt-library/2026-11-13-update-02/manifest.json) önceki 72 pine eklenen **27 pin / 62 görsel + 1 video / 63 prompt** kaydını tutar. 10 görsel önceki dosyalarla birebir aynıdır. İlk [72 pin / 107 kayıt / 102 farklı dosya](references/prompt-library/2026-11-13/manifest.json) ve daha eski [23 pin / 32 statik görsel kaydı](references/branding-board-2026-11-13.json) korunur. Bir sonraki karşılaştırmada ilk ve ikinci envanterin pin kimliklerini birlikte kullan; eski P001–P072 kimliklerini yeniden numaralama. Son güncellemede yeni pinlerin tüm slaytları incelendi; önceki 72 pinin slaytları baştan denetlenmedi. Video için örnek kare incelemesinin sınırı kendi kaydında yazılıdır. Envanterler tarihli gözlemdir; gelecekteki canlı pin sayısının kanıtı değildir.

1. Kısa linki çöz, temiz pano URL'sini kullan; davet anahtarlarını ve oturum bilgilerini saklama.
2. Pin/proje listesini sonuna kadar yükle. Karuselleri aç; videoları temsilî tek kapakla tamamlanmış sayma. Giriş veya yükleme sınırı varsa görünür kapsamı açıkça belirt. Yetkili açık tarayıcı oturumunu kullanabilirsin; erişilemeyen görsel için görmüş gibi yorum yapma.
3. Önceki pin kimlikleri ve görsel URL'leriyle karşılaştır. Aynı pindeki slayt değişimini de kontrol et. Yeni ve değişen içerikleri görsel olarak incele; eski içerikleri yalnız karşılaştırma gerektiğinde yeniden aç. Silinen pini otomatik olarak beğenilmeyen örnek sayma.
4. Bitmiş kimlik, reklam, font tanıtımı, hazır çizim/varlık, eğitim ve ürün/malzeme referanslarını ayır. Pin başlıkları yanıltıcı olabilir: görseli esas al. Aynı mockup'ın farklı fotoğrafı bağımsız estetik oy değildir.
5. Her yeni öğe için URL, görsel sayısı, gözlenen içerik, görünür kararlar ve sınırı kaydet. Uzun görselde küçük yazı okunamıyorsa kesin font, marka adı veya hex değeri uydurma.
6. Tekrar eden ilişkiyi **çıkarım** olarak yaz; farklı davranan örnekleri de kaydet. Kullanıcının açık geri bildirimini çıkarımdan ayrı tut. Yeni kanıt eski kuralı daraltıyorsa kuralı güncelle.
7. Tarihli yeni envanteri ve incelemeyi sakla; skill'in referans bağlantısını güncelle. Görülen pin sayısı, açılan alt görsel sayısı ve erişilemeyen içerikleri ayrı raporla. Bütün panoyu bitirmeden tamamlandı deme.

Kullanıcı tüm görselleri prompt’a dönüştürmeni istediğinde her pin/karusel slaytı için kaynak bağlantılı ayrı kayıt üret. Birebir tekrarların kaynak kimliğini koruyup ortak görsel dosyasına bağla; aynı tasarımın farklı çözünürlüklerini ayrıca işaretle. Bir kolaj tek kaynak görselse içindeki panel görevlerini prompt’ta açıkla; indirilmiş ayrı slaytlarmış gibi sayma. Yazılı prompt kapsamı ile bu prompt’lardan üretilmiş/denetlenmiş çıktı kapsamını ayrı belirt.

Kullanıcı panoyu güncelleyip gönderdiğinde bu döngüyü uygula. Arka planda kendiliğinden izleme veya otomatik öğrenme sözü verme; zamanlanmış takip yalnız ayrıca istenirse kurulur.
