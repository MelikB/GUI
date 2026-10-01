# Dünya'nın Doğuşu

Dünya'nın 4,57 milyar yıllık oluşumunu adım adım canlandıran, tarayıcıda çalışan etkileşimli bir simülasyon.

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

## Görünümler

Kamera her bölümde otomatik olarak uygun görünüme geçer. Sahnenin üstündeki düğmelerle istediğiniz görünüme kendiniz de geçebilirsiniz:

- **Yörünge**: gezegenin uzaydan görünümü
- **Yüzey**: 3D manzara ve atmosfer. Gökyüzü rengi, bulutlar, yağmur, Ay'ın gökteki boyutu ve atmosfer katmanları döneme göre değişir.
- **İç yapı**: gezegenden bir dilim çıkarılmış 3D kesit. Kabuk, manto, dış ve iç çekirdek ile manyetik alan çizgileri görünür.

3D görünümlerde sürükleyerek etrafınıza bakabilirsiniz.

Sağdaki panelde her an için sıcaklık, basınç, kütle, gün uzunluğu, Ay mesafesi, çekirdek yarıçapı ve atmosfer bileşimi gösterilir.

## Kontroller

- **Oynat / Duraklat**: alttaki düğme veya boşluk tuşu
- **Zaman çizelgesi**: tıklayıp sürükleyerek istediğiniz ana gidin. Çizelge odaktayken ← → ile ilerleyin, PageUp / PageDown ile bölüm atlayın.
- **Hız**: hız düğmesi 0,5×, 1×, 2× ve 4× arasında geçiş yapar
