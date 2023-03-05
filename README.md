# C#Form-Fis-Fatura-Gelir-Sistemi
C#Form ile visual studio ve SQL kullanarak bir fiş/fatura gelir sistemi yaptım. Biliyorsunuz ki bazı şirketler belirli fiş veya faturalardan belli bir gelir elde edebiliyor. Bunu yapan bir şirkete gittiğimde çalışanların hepsinin ayrı ayrı excel dosyalarına kendi verilerini kaydettiğini gördüm. Bende neden bütün fiş veya faturalar tek bir yere kaydedilmiyor ve bu işi neden tek bir kişi yapmıyor diye düşündüm ve ortaya böyle bir proje çıktı. 

![fişgiriş](https://user-images.githubusercontent.com/95971738/222973598-47a6b39b-51e3-4dd5-8f55-ad47f615dbd1.PNG)

Her zamanki gibi giriş kısmı.

![fişanasayfa](https://user-images.githubusercontent.com/95971738/222973608-a046a79d-d871-4077-be1c-e9e2b63158e6.PNG)

Anasayfa kısmı. Önce personel kısmına bakalım.

![fişpersonelekle](https://user-images.githubusercontent.com/95971738/222973623-9b311039-f2a0-48b0-a467-472d8f6e8f1d.PNG)

Bu kısımda basit bir personel kayıt yeri var. Çünkü her personelin kendine ait fişleri var ve bu fişleri ayırmak için sistemimize personelleri kaydetmemiz gerekiyor. Personellerin verilerini de güncelleyebiliyoruz.

![fişekle](https://user-images.githubusercontent.com/95971738/222973677-7a7f4cc2-770c-40b7-91b4-f73f35b3b4bd.PNG)

Burası projenin en önemli kısmı sayılır. Bu kısımda fişlerin girişini yapıyoruz. Tabiki bazı şirketler fiş veya faturalardan farklı gelirler elde edebiliyor. Ben şuanlık toplam fiyatın %2'si olarak ayarladım (Gördüğüm şirkette öyleydi.). Burada girilmesi gereken bilgilerin hepsini giriyoruz. Verilerimizi görebiliyoruz, güncelleme yapabiliyoruz. Arama kısmında ise belli tarih aralıklarında girilen fişleri veya faturaları inceleyebiliyoruz. 

Personel id'yi açıklayayım. Her personelin kendi id'si var. Örneğin kaan 123 gibi. Sistemde olmayan bir id'ye fiş giremiyoruz. Böylece yanlışlıkların önüne geçebiliyoruz. Şimdi gelir hesapla kısmına bakalım.

![fişkazanç](https://user-images.githubusercontent.com/95971738/222973865-abbd9607-7194-45d1-a11c-db194d9e0685.PNG)

Bu kısımda belli bir tarih aralığında, seçilen bir personelin o ayki kazancını görebiliyoruz. 

Tabiki bu proje geliştirilebilir. Mesela görüntü işleme ile sisteme fiş veya fatura girişini sadece kamera görüntüsüyle bile yapabiliriz. Sadece bu proje değil, her proje her zaman gelişebilir. Çünkü bu meslekte her an her şey değişebilir.

Umarım projemi beğenirsiniz.
