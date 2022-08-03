# Women-in-tech-academy-bitirme-projesi

![thumbs_b_c_5d9b627667b2e657ec682ed8ee6e6b91](https://user-images.githubusercontent.com/44268599/182632241-2ad9d166-def3-4b6a-8c13-1eb2a69d3774.jpg)

Herkese merhaba!

SistersLab’in Toplum Gönüllüleri Vakfı tarafından desteklenen Women in Tech Academy proje katılımcılarından biriyim. Proje, 20–28 yaş aralığındaki 25 kadını 3 ay boyunca yazılım eğitimleriyle güçlendirerek sektörde iş gücüne katılımını hedefliyor. Projeyle ilgili daha fazla bilgiye https://sisterslab.co/women-in-tech-academy/ adresinden ulaşabilirsiniz.

Women in Tech Academy bitirme projesi NBA'den alınan maç, oyuncu, takım gibi bilgileri içeren 5 adet csv dosyasının analiz edilmesi ve görselleştirilmesi işlemlerini içermektedir. Bu proje kapsamında yararlandığım veri setlerine data kısmından ulaşabilirsiniz.

# Veri Setleri Hakkında Bilgilendirme
- Teams Veri Seti: Takımların ID'leri, isimleri, şehirleri, arena vb. bilgileri içerir.
- Players Veri Seti: Oyuncuların isimleri, ID'leri ve oynadıkları takımlar hakkında bilgiler içerir
- Games Veri Seti: Oyunun oynandığı tarih, oyun ID'si, Ev sahibi ve Misafir takıma ait bilgiler içerir.
- Ranking Veri Seti: Takım ID'si, oyun sayısı, kazanma sayısı,kaybetme sayısı gibi bilgileri içerir.
- Games Details Veri Seti: Maçlara ve oyunculara ait daha detaylı bilgileri içerir.

# Analizde Kullanılan Kütüphane 
Pandas kütüphanesi kullanılarak analiz ve görselleştirme işlemleri gerçekleştirilmiştir.

# Önişleme
- NaN değer içeren verilerin bazıları ortalama değerler ile dolduruldu, bazıları silindi.
- Duplicate değerlerin varlığı kotrol edildi.
- Aynı değerlere sahip sütunlardan bir tanesi çıkarıldı.

# Yapılan Analiz ve Görselleştirmeler
Yapılan analiz ve görselleştirmelerden bir kaç örnek aşağıda yer almaktadır. Detaylara kodların yer aldığı dosyadan erişebilirsiniz.

- Takımların arena büyüklükleri 

![arena_büyüklüğü](https://user-images.githubusercontent.com/44268599/182625200-05ae0e0e-cd34-47cf-8cbe-9ccddd858bab.png)

- Yıllara göre kaç takım kurulduğu bilgisi 

![her_yıl_kaç_takım_kurulduğu](https://user-images.githubusercontent.com/44268599/182625398-c8722ccf-dacc-4b0f-9199-44fae6e49053.png)

- Her sezonda kaç adet oyuncunun yer aldığı

![her_sezonda_kaç_oyuncunun_yer_aldığı](https://user-images.githubusercontent.com/44268599/182625726-af4d5d41-038d-4b1f-8416-b06c2f890ef3.png)

- Takımdaki her oyuncunun kaç sezondur o takımda oynadığı

- Ev sahibi takımların maçları kazanma yüzdesi

![ev_sahibi_kazandı_mı](https://user-images.githubusercontent.com/44268599/182626280-ff97161a-2b64-48b5-9f06-f25582c721b0.png)

- Sezonlara göre ev sahibi takımın kazanması durumu

![sezon_ev_sahibi](https://user-images.githubusercontent.com/44268599/182626571-3160b112-e832-474f-b81e-06c2a5cc6910.png)

- En çok maç yapılan günde ev sahibinin kazanma yüzdesi

- Arena kapasitesinin ev sahibi takımın kazanmasına etki yüzdesi

- Maçların Liglere göre dağılım oranı

![lig](https://user-images.githubusercontent.com/44268599/182627158-502450f6-ef0d-43d2-a402-6f9c42e29588.png)

- Geri Dönüş yapmanın kazanma üzerine etkisi

- Her maçta kaç oyuncu olduğu ve en başarılı oyuncu

