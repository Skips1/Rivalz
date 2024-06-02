<h1 align="center">Rivalz</h1>

> Selamlar, teşvikli Rivalz node va app testleri yaptım. Katılırken bir çok şey öğreneceğinizi düşünüyorum

> Ben hetzner'den yaptım bunu fakat kendi sunucu sağlayacınızda da benzer şeyleri yaparsınız (olmadı contabocular pR atar)

> Donanım kısmı için her sunucu olur, sunucunuz ne kadar iyise o kadar rewards demek, miner olcaz sonuçta..

#
<details>
  <summary> <h1> Hetzner VPS Windows Kurulumu</summary> </h1>
    
<h1 align="center">Sadece Hetner VPS için geçerlidir</h1>


> Windows Server 2019 Englishi bul - Mouth butonuna tıkla - 3. numarada ki ikona tıkla ve sunucuna bağlan

![image](https://github.com/ruesandora/Rivalz/assets/101149671/d0ea7c04-2998-4447-bf6e-62610b76ee5d)

> Açılan yeni sekmede sunucu bilgilerinizi girmenizi isteyecek. 

> Açılan sekmede Ctrl + Alt + Del butonu var sağ altta, tıklıyoruz sonrasında windows kurulumu başlayacak.

> Gui seçeneğini seçmeyi unutmuyoruz.

> Sonrasında mavi arkaplanlı kısıma geçicek hiç bir ayarı değiştirmeden Nexte bas ardından Install Now butonuna tıklıyoruz. 

> Sonrasında 2. sıradaki Desktop Experince yazana tıklıyoruz.

![image](https://github.com/ruesandora/Rivalz/assets/101149671/a09a37af-48c8-43ce-9ae8-007e65ed306f)

> Sonraki aşamada Custom: Install Windows only yazana tıkla ve Hetzner paneline geri dön. 

> Bu sefer Iso Images kısmına Virtio yazın ve fotodaki işaretli sürümü mounth edin.

![image](https://github.com/ruesandora/Rivalz/assets/101149671/0c2b193d-aa76-477a-8a4a-e9aef71dc765)

> Sunucuya geri dönün ve Load Driver butonuna tıklayın, ardından görseldeki sürümü seçin.

![image](https://github.com/ruesandora/Rivalz/assets/101149671/c016e3b3-fff5-4831-8c0d-cff468c3091f)

> 3 Tane Driver göreceksiniz 3üne de delete işlemi yapın.

> Silme işlemi bittikten sonra New butonuna tıkla ve herhangi bir ayarı değiştirmeden direk Apply butonuna basalım. 

> Sonrasında gelen uyarıda yes butonuna tıklayalım.

![image](https://github.com/ruesandora/Rivalz/assets/101149671/3ca7fb7d-0860-4035-a86f-d91817ef8d5e)

> Şimdi Hetzner Paneline tekrar dönüyoruz Iso images kısmına tıklıyoruz.

> Ve arama yerinden Windows Server 2019 Englishi tekrar mounth et.

![image](https://github.com/ruesandora/Rivalz/assets/101149671/ad01131d-99ff-4db5-88fb-4b749bbe2b9b)

> Sunucuya geri dön, Refresh butonuna bas Next butonuna bas. Windowsun kurulmasını bekle.

![image](https://github.com/ruesandora/Rivalz/assets/101149671/a07cb8bb-9327-4d1b-9fc5-e9e759c981e6)

> Sunucumuza off/on yapıyor tekrar bağlanıyoruz.

> Akabinde şifre belirleme alanı geliyor burda 8 haneli bir şifre girin büyük harf istiyor

![image](https://github.com/ruesandora/Rivalz/assets/101149671/8d513ee7-7302-47b4-8a31-0fa04f5c2d61)

> Windowsun kilit ekranı kısmına geldiğinizde sağ alttaki Ctrl + Alt + Del butonuna tıklayın ve masaüstüne geçiş yapın. 

> İlk açılışta Server Manager kısmı açılıyor. Alttaki görseli takip edin 3 ve 4. kısımdaki tikler fotodakiyle aynı olsun.

![image](https://github.com/ruesandora/Rivalz/assets/101149671/8f38a679-dea8-49a9-b931-4b01994a5173)

> Kurulum Aşaması bitti şimdi Ayar kısımlarına geçiyoruz.

> Hetznere geri dönün ve Iso Images kısmından bu sefer Virtio win 248i mounth edin

![image](https://github.com/enzifiri/Rivalz/assets/76253089/cc81709b-df3b-49e6-94e4-0b3f1717dfa3)

# Windows Kurulumunu tamamlayalım.

> Mavi arkaplanlı kısım gelecek hiç bir ayarı değiştirmeden Nexte bas ardından Install Now butonuna tıklıyoruz. 

> Sonrasında 2. sıradaki Desktop Experince yazana tıklıyoruz.

![image](https://github.com/ruesandora/Rivalz/assets/101149671/a09a37af-48c8-43ce-9ae8-007e65ed306f)

> Sonraki aşamada Custom: Install Windows only yazana tıklayın.

> Bu kısımı lütfen iyi okuyun atlarsanız diskiniz gözükmeyecektir.

> Load Driver butonuna tıklayın
> Browse butonuna tıklayın ve ardından D: disketindeki (177 ile başlayan) > virio-win klasörü > amd64 > 2k19 klasörünü seçin ve Ok butonuna tıklayın.
> Eğer doğru klasörünü seçtiyseniz Red Hat SCSI ... ile başlayan bir text gelecek onu seçip next butonuna bas.

![image](https://github.com/enzifiri/Rivalz/assets/76253089/1fc9b04f-d7f9-4bbf-9677-3e0f2a89e0dc)

> New butonuna bas, hiç bi ayar değişmeden Apply butonuna bas ve Next yap.

![image](https://github.com/enzifiri/Rivalz/assets/76253089/7a6a13cb-72c5-4cd7-940d-dd0a8043e613)

> Sunucumuza off/on yapıyor tekrar bağlanıyoruz. (EĞER SİYAH EKRANDA KALDIYSANIZ BUNU YAPIN NORMALDE OTOMATİK YAPIYOR)

> Akabinde şifre belirleme alanı geliyor burda 8 haneli bir şifre girin büyük harf istiyor

![image](https://github.com/ruesandora/Rivalz/assets/101149671/8d513ee7-7302-47b4-8a31-0fa04f5c2d61)

> Windowsun kilit ekranı kısmına geldiğinizde sağ alttaki Ctrl + Alt + Del butonuna tıklayın ve masaüstüne geçiş yapın.
![image](https://github.com/enzifiri/Rivalz/assets/76253089/1796694a-5a90-479d-9c98-6682684c5a3b)

> İlk açılışta Server Manager kısmı açılıyor. Alttaki görseli takip edin 3 ve 4. kısımdaki tikler fotodakiyle aynı olsun.

![image](https://github.com/ruesandora/Rivalz/assets/101149671/8f38a679-dea8-49a9-b931-4b01994a5173)

# Windows Server Ayarlarımızı tamamlayalım. 

> Şifreyi ayarlayıp giriş yaptıktan sonra Windows logosuna sağ tıkla ve Device Manageri seç.

![image](https://github.com/ruesandora/Rivalz/assets/101149671/9fb7f205-719c-481f-8051-ad88603a0328)

> Açılan ekranda Other Devices bölümünde 3 veya 4 tane Sarı ünlem görüyorsunuz

> Önce Ethernet yazana sağ tık yapın ve update driverse tıklayın.

> Browse my computer... yazanı seç ve fotoğraftaki adımları takip et

![image](https://github.com/enzifiri/Rivalz/assets/76253089/e207a615-4ac1-40fb-a087-b1fe919b1660)


> Sağ kısımda Mavi panel açılacak Network başlıklı, Yes butonuna basın. 

> Geri kalan 2 veya 3 Adet sarı ünleme aynı işlemleri yapın.

#

> Windows logosuna tıklayın ve arama yerine Remote Desktop Settings yazın.

> Açılan ekrandaki Enable Remote Desktop kısmını aktif edin.

![image](https://github.com/ruesandora/Rivalz/assets/101149671/448d8fd2-e841-4719-b95b-a765faf9e707)


> Kişisel bilgisayarınızda Uzaktan Masaüstü bağlantı programı var onu açın.

> Mac'de Microsoft Remote Desktop - Windows'da Windows Remot isminde olmalı.

> Sunucu bilgilerinizi yazıp bağlanın.
> Kullanıcı Adı: Administrator
> Şifre: Windows kururken girdiğiniz şifre
![image](https://github.com/enzifiri/Rivalz/assets/76253089/454b08a5-bdf5-4c1b-b9a9-3b31cc7ac67b)

# Windows kurulumu bitti, Şimdi Rivalz Nodeu kurmaya devam edebilirsiniz.

</details>

<details>
  <summary> <h1> Ubuntu VPS Sunucu Kurulumu </summary> </h1>
    <h1 align="center">Sadece Ubuntu için geçerlidir</h1>
    
> Sunucuya bağlandığınızı farz ederek devam ediyorum.
> Sunucu güncelleme, libfuse2 ve gereklilikleri yüklüyoruz.
```
sudo apt update -y && sudo apt upgrade -y
```
```
sudo apt-get install -y gconf-service libasound2 libatk1.0-0 libc6 libcairo2 libcups2 libdbus-1-3 libexpat1 libfontconfig1 libgcc1 libgconf-2-4 libgdk-pixbuf2.0-0 libglib2.0-0 libgtk-3-0 libnspr4 libpango-1.0-0 libpangocairo-1.0-0 libstdc++6 libx11-6 libx11-xcb1 libxcb1 libxcomposite1 libxcursor1 libxdamage1 libxext6 libxfixes3 libxi6 libxrandr2 libxrender1 libxss1 libxtst6 ca-certificates fonts-liberation libappindicator1 libnss3 lsb-release xdg-utils wget libgbm-dev libnss3-dev libfuse2
```
![image](https://github.com/awelmisin/Rivalz/assets/73443933/72cb8fa9-4079-47f1-a41f-5b609cc4a3a1)

> ekran açalım.
```
screen -S rivalz
```

> rivalz clienti indirelim.
```
wget https://api.rivalz.ai/fragmentz/clients/rClient-latest.AppImage
```
![image](https://github.com/awelmisin/Rivalz/assets/73443933/c1393ff3-f43b-4b3b-8620-79db8c937b50)

> indirdiğimiz dosyayı executable yapalım.
```
chmod +x rClient-latest.AppImage
```
![image](https://github.com/awelmisin/Rivalz/assets/73443933/cb35396c-4c4b-4f16-ad0a-ab7ed3ca0501)

> dosyayı açalım.
```
./rClient-latest.AppImage --no-sandbox
```
![image](https://github.com/awelmisin/Rivalz/assets/73443933/e556d8ba-64d0-4bf9-aec6-02beb0ae9fb4)
> bir sorun çıkmaz ise karşınıza bu ekran gelecek.
> 
> bundan sonra storage belirleyip, wallet girerek yapabilirsiniz. tebrikler! linuxda rclient açabiliyorsunuz artık.

![image](https://github.com/awelmisin/Rivalz/assets/73443933/0ab8f196-0c17-44bc-b536-e1a25445357a)

</details>

# Rivalz Node Kurulumu

> Rivalz hesap açıyoruz [buradan](https://rivalz.ai?r=Ruesandora0)

> Burada cüzdan, twitter ve discord her şey bağlayın.

#

> Remote ile bağlandığımız ekrana geri dönüyoruz.

> Microsoft Edge'i indiriyoruz Remota'a (suncuya)

> rivalz.ai sitesine girip dowland windows diyoruz

> Kurulumu yapıyoruz

#

> Kurulum tamamlandıktan sonra, önce metmaask cüzdan adresimizi giriyoruz

> Storage Control'den free space neye müsade ediyorsa o rakamı giriyoruz

> Sonra başlatıyoruz node'u ve hayırlı olsun.

>  rClient uygulamasında sol üstte view sekmesi var oradan reload'a basıp, node'u tekrar çalıştırın

<img width="1251" alt="Ekran Resmi 2024-05-25 00 38 38" src="https://github.com/ruesandora/Rivalz/assets/101149671/cdf68d07-c897-4e5a-93d8-b34e2c4a82ee">

#

> Akabinde rivalz'da LOYALTY NFTs kısmını yapmayı unutmayın mintlein 10 NFT'yi.

> Rivalz hakkında link paylaşmak isterseniz [burayı](https://t.me/ruesshare/21528) kullanabilirsiniz.
