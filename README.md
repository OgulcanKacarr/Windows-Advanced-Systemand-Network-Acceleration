
# advanced network and system acceleration for Windows 10

## (Windows Check for Updates) Windows Güncellemeleri kontrol et

* İlk olarak, Windows'un güncel olup olmadığını kontrol edin. Güncel değilse, güncelleyin.
- First, check if windows is up to date. If it's out of date, update it.
## ===============================<br>
## (windows performance mode) windows'u performans moda alın 

* Oyuncu değilseniz ve animasyon, efekt gibi özellikleri önemsemiyorsanız bu özellikleri kapatın.
- If you are not a gamer and you don't care about features like animations, effects, turn these features off.

 [+] Bu bilgisayar > özellikler > gelişmiş sistem özellikleri > performans > en iyi performans için ayarla <br>
 [-] This computer > properties > advanced system properties > performance > adjust for best performance


![performance](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/performanceControl.png)<br>

 [+] Etkinleştirdikten sonra metinler bozulabilir. Metinleri düzeltmek için; <br>
 [+] After activating it, the texts may be corrupted. To correct the texts;<br>
  * denetim masası > Görünüm ve kişiselleştirme > yazı tipi > ClearType metnini ayarla<br>
  * control panel > Appearance and personalization > font > clear type <br> <br>
 ![clearType](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/clearType.png)<br><br>
## ===============================<br>
## (Background image removal) Arkaplan resmini kaldırma

* Bir masaüstü arka plan resmi kullanıyorsanız, onu kullanmanıza gerek yoktur. Çünkü masaüstünüzü başka bir yerden açmak istediğinizde, Windows açmak istediğiniz görüntüyü bulduktan sonra size masaüstünü gösterecektir. Bu gereksiz ve performansı düşüren bir süreçtir. Sadece siyah arka plan kullanın. Ve Windows'u her yerden karanlık moda alın veya her şeyi siyah kullanın.


* If you are using a desktop background image, you don't need to use it. Because when you want to open your desktop from another place, windows will show you the desktop after finding the image you want to open. This is an unnecessary and performance-degrading process. Just use black background. and put windows in dark mode from everywhere or use everything in black.
## ===============================<br>
## (Data cleaning) Veri Temizleme

* Bilgisayarınızdaki verileri düzenli olarak temizleyin.
* Clean data regularly on your computer.

windwos + R (çalıştırı açın) ve temp ve %temp% yazın. Ardından buradaki her şeyi silin. Silinmeyenleri atlayabilirsiniz.
windwos + R (open run) and type temp and %temp%. Then delete everything here. if there are files that are not deleted, you can skip them.


 ![temp](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/temp.png)<br><br>
 ![ttemp](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/ttemp.png)<br><br>
 ![deltemp](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/deltemp.png)<br><br>
 
 * Ardından bilgisayarı açın ve sabit disk özelliklerini açın. Ardından diske tıklayın. Tüm kutuları seçin ve diski temizleyin
 * Then open computer and name hardisk properties. Then click  disk. Select all the boxes and clean the disk

 ![properties](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/propertiesDisk.png)<br><br>
 ![allselect](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/allselect.png)<br><br><br>

* Bilgisayarda "yazılabilir" dosyaları temizleme;
* Cleaning files that are "writable" on the computer;

Cmd'yi açın ve "cipher /w:c" komutunu girin. Böylece c diskiniz bu durumdan kurtulacaktır.<br>
Open cmd and enter the command "cipher /w:c". So your c disk will get rid of this situation.

 ![cmd](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/cmd.png)<br><br>

## ===============================<br>
# İleri Seviye Network Hızlandırma
# Advanced network acceleration
## ===============================<br>

Bilgisayarlarda ağ performansı sınırlıdır. Hiçbir işletim sisteminde ağ ortamı için tam performans alamıyoruz. Bunun temel nedeni RFC beyanlarına uymaktır. Başka bir deyişle, dünya çapında ağ hakkında yapılan yorumları değerlendirerek karar verilen bazı ifadeler vardır ve bilgisayarlar da bu açıklamada alınan kararları uygular. Bu durum ağlarda tam performans almamızı kısıtlıyor. Başka bir deyişle, RFC her zaman performanstan çok kararlılığı vurgular. Başka bir deyişle, RFC'nin her şeyin hızlı olmasını her şeyin yolunda olmasını tercih ettiğini söyleyebiliriz. Windows, yakında yapacağımız eylemleri önerir. Ancak, bunları varsayılan olarak uygulamaz. Bunun nedeni, az önce söylendiği gibi RFC kararlarına bağlı kalmasıdır. <br>

Network performance on computers is limited. We do not get full performance for network environment in any operating system. The main reason for this is to comply with the RFC declarations. In other words, there are some statements that are decided by evaluating the comments made about the world-wide network, and computers also implement the decisions taken in this statement. This situation limits us to get full performance on networks. In other words, RFC always emphasizes stability over performance. In other words, we can say that the RFC preferred everything to be fine over everything being fast. Windows itself suggests the actions that we will do soon. However, it does not implement them by default. The reason for this is that it adheres to RFC decisions, as it has just been said. <br>

* şimdi windows + R yaparak "run"u açalım ve "regedit" yazalım <br>
* now let's open "run" by doing windows + R, and type "regedit" <br>
*  ![regedit](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/regedit.png)<br><br>
*  Öncelikle önlem almak için regedit dosyalarımızın yedeğini alalım. <br>
*  First of all, let's take a backup of our regedit files to take precautions. <br>
* Dosya > ver > masaüstüne kaydet <br>
* File > export > save to desktop <br>
* ![backup](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/backup.png)<br><br>
* ardından bu konuma gidin >>>> Bilgisayar\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\Tcpip\Parameters <br>
* then navigate to this location >>>> Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\Tcpip\Parameters <br>
* ![regedit1](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/regedeti1.png)<br><br>
* Buraya sağ tıklayarak bir "dword32" değeri oluşturalım. <br>
* Let's create a "dword32" value by right-clicking here. <br>
* ![dword32](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/dword32.png)<br><br>
* Şimdi bu şekilde gösterdiğim her şeyi resimlerdeki gibi ekleyin. <br>
* Now add everything I have shown in this way as in the images. <br>
* ![value1](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/value1.png)<br><br>
* ![value2](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/value2.png)<br><br>
* ![value3](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/value3.png)<br><br>
* ![value4](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/value4.png)<br><br>
* ![value4.1](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/value7.png)<br><br>
* ![value4.2](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/value8.png)<br><br>
* ![value4.3](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/value10.png)<br><br>
* ![value4.4](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/value11.png)<br><br>
* ![value4.5](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/value9.png)<br><br>
*  ![value4.6](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/value12.png)<br><br>
* ![value4.7](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/value13.png)<br><br>
* ![value4.8](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/value14.png)<br><br>
* ![value4.9](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/value15.png)<br><br>
* Şimdi "interfaces" sekmesine gidelim. Burada ip adresinizi gösteren bölümü bulun. <br>
* Now let's go to the "interfaces" tab. Find the section that shows your ip address here. <br>
* ![interfaces](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/interfaces.png)<br><br>
* resimlerdeki değerleri eklemeye devam edin. <br>
* keep adding the values in the pictures. <br>
* ![value5](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/value5.png)<br><br>
* ![value6](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/value6.png)<br><br>
* ![value5.1](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/value16.png)<br><br>
* ![value6.1](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/value17.png)<br><br>
* şimdi komut satırını açın ve resimlerde gördüğünüz komutları girin <br>
* now open the command line and enter the commands you see in the pictures <br>
* "netsh int tcp set global dca=enable"
* ![cmd1](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/comman1.png)<br><br>
* "netsh int tcp set global netdma=enable"
* ![cmd2](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/command2.png)<br><br>
* "netsh int tcp set global ecncapability=disabled"
* ![cmd3](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/command4.png)<br><br>
* "netsh int tcp set supplemental custom congestionprovider=ctcp"
* ![cmd4](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/command5.png)<br><br>
* şimdi bu konuma gidin > Bilgisayar\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\Tcpip\ServiceProvider <br>
* now go to this location > Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\Tcpip\ServiceProvider <br>
* ![cmd4](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/dnss.png)<br><br>
* resimlerdeki değerleri eklemeye devam edin. <br>
* keep adding the values in the pictures. <br>
* ![dns1](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/dns1.png)<br><br>
* ![dns2](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/dns2.png)<br><br>
* ![dns3](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/dns3.png)<br><br>
* ![dns4](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/dns4.png)<br><br>
* şimdi bu konuma gidin > Bilgisayar\HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\ <br>
* now navigate to this location > Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\ <br>
* burada "Psched" adında bir klasör oluşturun. <br>
* create a folder named "Psched" here. <br>
* ![psc](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/psc.png)<br><br>
* resimlerdeki değerleri eklemeye devam edin. <br>
* keep adding the values in the pictures. <br>
* ![psc2](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/psc2.png)<br><br>
* şimdi bu konuma gidin >>> Bilgisayar\HMAKEY_CHINE\SYSTEM\CurrentControlSet\Services\Tcp <br>
* now go to this location >>> Computer\HMAKEY_CHINE\SYSTEM\CurrentControlSet\Services\Tcp <br> 
* burada "QoS" adında bir klasör oluşturun. <br>
* create a folder named "QoS" here. <br>
* ![tcp1](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/tcp1.png)<br><br>
* resimlerdeki değerleri eklemeye devam edin. <br>
* keep adding the values in the pictures. <br>
* ![tcp2](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/tcp2.png)<br><br>
* şimdi komut satırını açın ve bu komutu girin >>> netsh int tcp set global autotuninglevel=disabled <br>
* now open command line and enter this command >>> netsh int tcp set global autotuninglevel=disabled <br>
* ![tcp2](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/command6.png)<br><br>







