# ⭐WOMAN IN TECH ACADEMY BİTİRME PROJESİ ⭐
# ⭐ OLİMPİYAT OYUNLARI VERİ ANALİZİ ⭐

![image](https://user-images.githubusercontent.com/53252601/202868693-75ec2fc7-1955-406b-89cb-6ab969db815f.png)


**Veri Seti Hakkında**

Veri setinde Atina 1896'dan Rio 2016'ya kadar olan 120 yıllık tüm olimpiyat müsabakalarının katılımıcılarının özellikleri yer almaktadır.  

Kış ve Yaz Oyunlarının 1992'ye kadar aynı yılda yapılmıştır. 1992'den sonra , Kış Oyunları 1994'ten başlayarak dört yıllık bir döngüde, ardından 1996'da Yaz, ardından 1998'de Kış vb bir periyod ile yapıldığını belirtmekte fayda var.

**Veri Seti İçeriği**

* Veri seti içinde "athlete_events.csv" ve "noc_regions.csv" dosyaları bulunmaktadır;
* athlete_events.csv - > 271116 satır ve 15 sütun bulunmaktadır.
* Her satır bir yarışmacıyı belirtmektedir.
* noc_regions.csv -> 230 satır ve 3  sütun yer almaktadır.


    **athlete_events.csv - > dosyasındaki sütunlar:**
    * ID - Her sporcu için ID numarası
    * Name - Sporcu isimleri
    * Sex - Kadınlar için 'F' ve Erkekler 'M' 
    * Age - Yaş
    * Height - Yarışmacı boyu (cm)
    * Weight - Yarışmacı kilosu (kg)
    * Team - Takım ismi
    * NOC - Ulusal Olimpiyat Komitesi 
    * Games - Yıl ve mevsim
    * Year - Yıl
    * Season - Yaz ve Kış (Summer or Winter)
    * City - Ev sahibi şehir
    * Sport - Spor branşı
    * Event - Etkinlik
    * Medal - Gold, Silver, Bronze, or NA

    **noc_regions.csv  - > dosyasındaki sütunlar:**
    * NOC - Ulusal Olimpiyat Komitesi
    * region - bölge
    * notes - notlar

**Amacımız**

Olimpiyat veri setinde yer alan verilere göre, kadınların,erkeklerin, farklı ulusların ve farklı spor ve etkinliklerin katılımı ve performansı hakkında olimpiyatların zaman içinde nasıl geliştiği, değiştiği, kazanılan madalyaların en çok hangi ülke,sporcu,etkinlik, branş dalı vb. kazanıldığı hakkında sorular sorarak analizler yapmaktır. 



### ⭐⭐⭐  NELER YAPTIM ⭐⭐⭐

**⭐ 1 ) Veri Seti Üzerinde yapılan işlemler**

 1.1 ) Veri setlerini okuma ve veri setlerii hakkında bilgi sahibi olma 
 
 1.2 ) Merge İşlemi
                
![data](https://user-images.githubusercontent.com/53252601/202869188-fb1d8d68-ebe0-4ef3-809d-09b9443194bb.png)

1.3 ) Null değerler üzerinde drop ve fill işlemleri
                
![image](https://user-images.githubusercontent.com/53252601/202869139-9e525260-9de2-41e4-a2f0-ee94a1d941fe.png)


**⭐ 2 ) Temizlenen Veri Seti Üzerinde İşlemler**

 **2 . 1) Tek Değişkenli Analiz**

 **2.1.1) Sayısal verilerde Histogram ve kutu grafikleri ile analizler**
1) Sayısal Değişkenler:
* Age
* Height   
* Weight   
* Year


![image](https://user-images.githubusercontent.com/53252601/202869334-063710cb-c697-43a8-bc67-0e0534238903.png)
![image](https://user-images.githubusercontent.com/53252601/202869309-cb8be4a3-35e9-45ce-8488-981934fa4146.png)
![image](https://user-images.githubusercontent.com/53252601/202869346-1c233139-5c9b-4a8b-a1e6-c3a546923c7f.png)
![image](https://user-images.githubusercontent.com/53252601/202869357-3d0f7783-2fb8-439e-9698-90afa05a4cac.png)


**a) Outlier Analizi**

* Yaşı 70'den büyük olan olimpiyat katılımcılarına bakalım
* Boyu 210 cmden büyük olimpiyat katılımcıları
* Kilosu 175 kg büyük olimpiyat katılımcıları

![image](https://user-images.githubusercontent.com/53252601/202869540-6787c9ff-c17c-434c-8357-df2740c5378e.png)
![image](https://user-images.githubusercontent.com/53252601/202869548-28d4587a-7402-4260-b1db-18cf6333b741.png)
![image](https://user-images.githubusercontent.com/53252601/202869551-6ad5db2e-7eaf-412b-b924-7b157a3725e6.png)

                    
**2.1.2) Kategorik verilerde bar grafikleri ile analizler**


![image](https://user-images.githubusercontent.com/53252601/202869648-9815e51b-5af4-4c47-ad07-91a67049037b.png)
![image](https://user-images.githubusercontent.com/53252601/202869657-2296a90f-d381-4850-b31b-206c0d7adb96.png)
![image](https://user-images.githubusercontent.com/53252601/202869662-4ca46ccc-d100-42c4-97cc-cae5480dd13b.png)
![image](https://user-images.githubusercontent.com/53252601/202869666-7ddc2635-d9a2-4687-8e46-62887ee92dfe.png)
![image](https://user-images.githubusercontent.com/53252601/202869671-30a57701-6e25-4a98-a5fe-4d54b14adda9.png)
![image](https://user-images.githubusercontent.com/53252601/202869709-eec51f5d-e833-403a-87d7-07b8c281ee24.png)
![image](https://user-images.githubusercontent.com/53252601/202869712-17d3512c-4458-45bb-a992-3233f562a18c.png)
![image](https://user-images.githubusercontent.com/53252601/202869713-595c5fe5-577c-4183-9991-064fcb3caa21.png)
![image](https://user-images.githubusercontent.com/53252601/202869721-82d35f5a-1b70-4cfb-8fdc-e5276a41da0e.png)
![image](https://user-images.githubusercontent.com/53252601/202869727-e8a65062-0915-4ff6-a51f-8aa9b12476ac.png)


**Madalya kazanan katılımcılar özelindeki analiz sonuçları şu şekilde özetlenebilir:** 

* En çok madalya alan isim Michael Fred Phelps'dir. 
* Madalya alan erkek yarışmacılar kadın yarışmacılardan yaklaşık 2 kat daha fazladır. 
* Olimpiyatlarda en çok madalya alan ülke ABD'dir. 
* Yaz mevsiminde düzenlen olimpiyatlar kış mevsiminden daha fazladır.
* Olimpiyatlar en çok Londra'da düzenlenmiştir.
* Olimpiyatlarda en çok atletizm branşında yarışılmıştır ve yine aynı en çok atletizm branşında madalya kazanılmıştır. 
* Erkekler futbol müsabakaları en çok yapılan etkinliktir.


**2.2) İki değişkenli Veri Analizi**
* 2.1 ) Korelasyon ilişkisi

![corr](https://user-images.githubusercontent.com/53252601/202869844-1c5abb8f-50a7-4e23-b382-9578a710911b.png)

* 2.2 ) Cinsiyete göre boy ve kilo karşılaştırmaları

![image](https://user-images.githubusercontent.com/53252601/202869874-f9ef860b-9dcb-476b-96c3-c7728ec11f97.png)
![image](https://user-images.githubusercontent.com/53252601/202869877-771a92ab-26f8-4723-b6fe-b8dfa9262bcc.png)

* 2.3 ) Takımların kazandıkları madalya sayıları

![teammadal](https://user-images.githubusercontent.com/53252601/202869945-35e789e6-bda0-4a92-9a3b-b4680aefd67b.png)

* 2.4 ) Yarışmacılara göre kazanılan madalyalar
* 2.5 ) Yarışmacılar ve spor alanına göre kazanılan madalyalar
* 2.6 ) Şehre göre kazanılan madalyalar
* 2.7 ) Cinsiyete göre kazanılan madalya sayıları
* 2.8 ) Yıla göre kazanılan madalyalar
* 2.9 ) Spor dalına göre cinsiyetlerin kazandığı madalyalar
* 2.10 ) Yıllara göre kadın ve erkek katılımcıların katıldığı olimpiyat sayılarının karşılaştırılması
![image](https://user-images.githubusercontent.com/53252601/202869896-a4b670fe-c188-45f4-87a9-e500834df61e.png)



**⭐3 ) PİVOT TABLE**

* 3.1 ) Madalya kazananların cinsiyete göre yaş boy ve kilo ortalamaları
* 3.2 ) Spor dallarına göre sporcuların boy, kilo ve yaş ortalamaları
* 3.3 )İstenilen bir spor dalı için cinsiyetlere göre kaç madalya kazanıldığı bulma


**⭐4 ) EN İYİLER ANALİZLERİ**

* 4.1 ) En fazla altın madalya kazanan 10 ülke
![image](https://user-images.githubusercontent.com/53252601/202870004-949e7d4d-9b80-4735-a21f-6f483b65078a.png)
                
* 4.2 ) Altın, Gümüş ve Bronz Madalya kazanan ilk 20 ülke

![image](https://user-images.githubusercontent.com/53252601/202870045-7d547d8e-c6f9-4a5b-8358-3cd97df738fc.png)
![image](https://user-images.githubusercontent.com/53252601/202870049-f905dfc9-b18a-4dde-b1d4-ddeea7c88b06.png)
![image](https://user-images.githubusercontent.com/53252601/202870055-97e38537-0bd2-420b-a172-aa45ac4bd005.png)

* 4.3 ) En fazla Altın, Gümüş ve Bronz Madalyanın kazanıldığı 10 yıl

![image](https://user-images.githubusercontent.com/53252601/202870069-cac5ee3b-5576-4c7d-87f8-efa96328a530.png)

* 4.4 ) En Fazla Madalya Kazanılan Etkinlikler

![madalyaetkinlik](https://user-images.githubusercontent.com/53252601/202870135-45ed9188-895a-4b0d-8b51-d761e4d50409.png)

* 4.5 ) Bir spor dalı için en başarılı yarışmacıları bulma analizi

![image](https://user-images.githubusercontent.com/53252601/202870163-fb01e593-99aa-4564-91ae-786cc34bc2da.png)

* 4.6 ) Bir ülkenin en başarılı olduğu spor dalını bulma analizi

![basarispor](https://user-images.githubusercontent.com/53252601/202870243-67d9c231-cecb-497b-82b8-2fe42437afd6.png)

* 4.7 ) Belli bir spor dalı için kilo ve boya göre kadın ve erkeklerin dağılımları

![image](https://user-images.githubusercontent.com/53252601/202870281-d6f0281b-c7ff-49da-aa5b-a1d3289e26a5.png)


**⭐5 ) ZAMAN SERİLERİNDE (TIME SERIES) VERİ ANALİZİ**

* 5.1 ) Yıllara göre ortalama yaş,boy,kilo değişimi

![image](https://user-images.githubusercontent.com/53252601/202870364-dabc32a8-6f75-4c65-9b21-2d066c2981ac.png)

![image](https://user-images.githubusercontent.com/53252601/202870373-4daffdb0-21c4-4019-be23-c53b06c8b219.png)

![image](https://user-images.githubusercontent.com/53252601/202870379-385f6994-bc77-4a28-b76a-8f01d74c066c.png)

![image](https://user-images.githubusercontent.com/53252601/202870389-f3839e30-b6f1-49e1-8575-c3a927fe8a6a.png)

* 5.2 ) Yıllara göre madalya sayıları

![image](https://user-images.githubusercontent.com/53252601/202870398-42e77493-4c05-422b-9e60-a8b6ee6cb651.png)


## ⭐⭐⭐⭐ ANALİZLERİMİN SONUNA GELDİK  ⭐⭐⭐⭐

## ⭐⭐⭐⭐ İNCELEDİĞİNİZ İÇİN TEŞEKKÜR EDERİM  ⭐⭐⭐⭐


![image](https://user-images.githubusercontent.com/53252601/202870676-d956d77a-f543-485c-b6fd-48e53cce2630.png)
                                      
                                                
                                                
Python ve Makine Öğrenmesi alanıyla ilgili hazırladığım Medium yazılarıma aşağıdaki linkten ulaşabilirsiniz.<br>
<a href="https://medium.com/@haticecandan">MEDIUM</a> <br>

Ayrıca Linkedln sayfama da göz atabilirsiniz.<br>
<a href="https://www.linkedin.com/in/haticecandan">LINKEDIN</a> 

