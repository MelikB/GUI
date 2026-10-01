# Dünya'nın Doğuşu

Dünya'nın 4,57 milyar yıllık oluşumunu anlatan, tarayıcıda çalışan etkileşimli bir belgesel simülasyon. Telefonda ve masaüstünde çalışır.

`index.html` dosyasını herhangi bir tarayıcıda açmanız yeterli. Kurulum ya da derleme gerekmez. 3D görünümler için three.js (r128) CDN'den yüklenir; yüklenemezse simülasyon 2D görünümlerle çalışmaya devam eder.

## Bölümler

1. **Güneş Bulutsusu**: Süpernova şok dalgası, bulutun çöküp dönen bir diske dönüşmesi, ön-Güneş'in parlaması.
2. **Gezegencikler**: Gerçek zamanlı N-cisim benzetimi. Gezegencikler kütleçekimiyle hareket eder, çarpışınca birleşir. Kar çizgisi (2,7 AU) ve AU ölçeği gösterilir.
3. **Ön-Dünya**: Kamera büyüyen embriyoya yaklaşır; erimiş yüzey ve sürekli çarpışmalar.
4. **Demir Yağmuru** (3D kesit): Demir damlaları magma okyanusundan çekirdeğe çöker, çekirdek büyür.
5. **Theia Çarpışması**: Parçacık fiziğiyle çarpışma, şok dalgası, Theia'nın demir çekirdeğinin Dünya'ya karışması ve enkaz diski.
6. **Ay'ın Doğuşu**: Roche sınırının içindeki malzeme Dünya'ya geri yağar, dışındaki parçacıklar ay tohumlarında toplanıp tek bir Ay'a dönüşür.
7. **Magma Okyanusu**: Erimiş yüzey ve çok yakındaki Ay.
8. **Soğuyan Gezegen** (3D kesit): Magma okyanusu dipten yukarı katılaşır, manto konveksiyonu başlar, ilk kabuk oluşur.
9. **İlk Yağmurlar** (3D yüzey): Kamera atmosferin içinden yüzeye iner. Buhar atmosferi, sağanaklar, şimşekler, volkanlar ve dolan okyanuslar.
10. **Okyanus Dünyası**: Geç Ağır Bombardıman ve jeodinamonun başlaması.
11. **Arkeen Kıyısı** (3D yüzey): Turuncu metan pusu, sönük Güneş, stromatolitler.
12. **Oksijen ve Buz**: Büyük Oksidasyon Olayı ve Kartopu Dünya.
13. **Bugünkü Dünya**: Ormanlar, mavi gökyüzü, Chicxulub çarpması ve şehir ışıkları.

Çarpışma ve Ay'ın oluşumu saatler ile yüzyıllar arasında sürdüğü için bu iki bölümde zaman, çarpışmadan bu yana geçen süreyle gösterilir.

## Belgesel modu

- Açılışta **Sesli izle** seçilirse her bölüm tarayıcının Türkçe konuşma sesiyle anlatılır. Anlatıcı konuşurken film onu bekler. Anlatım her zaman altyazı olarak da gösterilir.
- Her bölüm sinematik bir başlık kartıyla açılır.
- Ortam sesi Web Audio ile üretilir: uzayda alçak bir uğultu, magma döneminde gürleme, yüzeyde rüzgâr ve yağmur, çarpışmalarda patlama sesi.

## Bilim katmanı

Panelde üç sekme vardır:

- **Anlatım**: bölüm metni ve öne çıkan bilgiler
- **Veriler**: anlık ölçümler ve Dünya tarihi boyunca grafikler (sıcaklık, Güneş parlaklığı, oksijen, CO₂, iç ısı, gün uzunluğu, Ay mesafesi, kıtasal kabuk). Grafikler tablo olarak da görüntülenebilir.
- **Bilim**: her bölümün denklemleri, o anki değerlerle hesaplanmış sonuçları, kanıtları ve kaynak makaleleri

Fizikten hesaplanan büyüklükler:

- Güneş parlaklığı: Gough (1981), L/L₀ = [1 + ⅖(1 − t/t₀)]⁻¹
- Sera etkisi olmadan denge sıcaklığı: T = [S(1 − A)/4σ]^¼; yüzey sıcaklığıyla farkı sera ısınmasıdır
- Radyojenik ısı: ²³⁸U, ²³⁵U, ²³²Th ve ⁴⁰K bozunma sabitleriyle
- Gelgit kuvveti (∝ 1/d³), Ay'ın gökteki açısal boyutu, Roche sınırı, çarpışma enerjileri
- Gezegencik birikimi (N-cisim) ve Theia çarpışması (parçacık) simülasyonları

Oksijen, CO₂, sıcaklık ve kıtasal kabuk eğrileri literatürdeki derlemelere dayanan yaklaşık değerlerdir.

## Görünümler

Kamera her bölümde otomatik olarak uygun görünüme geçer. Sahnenin üstündeki düğmelerle istediğiniz görünüme kendiniz de geçebilirsiniz:

- **Yörünge**: gezegenin uzaydan görünümü
- **Yüzey**: 3D manzara ve atmosfer. Gökyüzü rengi, bulutlar, yağmur, Ay'ın gökteki boyutu ve atmosfer katmanları döneme göre değişir.
- **İç yapı**: gezegenden bir dilim çıkarılmış 3D kesit. Kabuk, manto, dış ve iç çekirdek ile manyetik alan çizgileri görünür.

3D görünümlerde sürükleyerek etrafınıza bakabilirsiniz.

Sağdaki panelde her an için sıcaklık, basınç, kütle, gün uzunluğu, Ay mesafesi, çekirdek yarıçapı ve atmosfer bileşimi gösterilir.

## Kontroller

- **Oynat / Duraklat**: alttaki düğme veya boşluk tuşu
- **Anlatıcı** ve **ortam sesi**: alttaki mikrofon ve hoparlör düğmeleri
- Telefonda panel aşağıdan açılır; tutamağa veya bir sekmeye dokunun
- **Zaman çizelgesi**: tıklayıp sürükleyerek istediğiniz ana gidin. Çizelge odaktayken ← → ile ilerleyin, PageUp / PageDown ile bölüm atlayın.
- **Hız**: hız düğmesi 0,5×, 1×, 2× ve 4× arasında geçiş yapar
