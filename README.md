
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
##Tcpip\Parameters Folders
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
##Interfaces Folders
* Şimdi "interfaces" sekmesine gidelim. Burada ip adresinizi gösteren bölümü bulun. <br>
* Now let's go to the "interfaces" tab. Find the section that shows your ip address here. <br>
* ![interfaces](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/interfaces.png)<br><br>
* resimlerdeki değerleri eklemeye devam edin. <br>
* keep adding the values in the pictures. <br>
* ![value5](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/value5.png)<br><br>
* ![value6](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/value6.png)<br><br>
* ![value5.1](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/value16.png)<br><br>
* ![value6.1](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/value17.png)<br><br>
##COMMANDS
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
##Tcpip\ServiceProvider Folders
* şimdi bu konuma gidin > Bilgisayar\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\Tcpip\ServiceProvider <br>
* now go to this location > Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\Tcpip\ServiceProvider <br>
* ![cmd4](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/dnss.png)<br><br>
* resimlerdeki değerleri eklemeye devam edin. <br>
* keep adding the values in the pictures. <br>
* ![dns1](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/dns1.png)<br><br>
* ![dns2](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/dns2.png)<br><br>
* ![dns3](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/dns3.png)<br><br>
* ![dns4](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/dns4.png)<br><br>
##Microsoft\Windows\ Folders
* şimdi bu konuma gidin > Bilgisayar\HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\ <br>
* now navigate to this location > Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\ <br>
* burada "Psched" adında bir klasör oluşturun. <br>
* create a folder named "Psched" here. <br>
* ![psc](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/psc.png)<br><br>
* resimlerdeki değerleri eklemeye devam edin. <br>
* keep adding the values in the pictures. <br>
* ![psc2](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/psc2.png)<br><br>
##\Services\Tcp Folders
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
##Programlar ve Özellikler 
* şimdi bu konuma gidin >>> Denetim Masası\Programlar\Programlar ve Özellikler <br>
* now go to this location >>> Control Panel\Programs\Programs and Features <br>
* ![controlp1](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/controlp1.png)<br><br>
* sonra resimlerdeki kutuları işaretleyin <br>
* then tick the boxes on the pictures <br>
* ![tick1](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/tick1.png)<br><br>
* ![tick2](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/tick2.png)<br><br>

Ve evet, hepsi bu. Artık ağınız diğer bilgisayarlardan daha hızlı.
And yes, that's all. Now your network has more speed than other computers.
## ===============================<br>

# (System Acceleration) Sistem Hızlandırma

Ağı çözdük, şimdi aynı şeyleri sistemimize yapalım. Bizim sistemimizde de aynı nedenlerle kısıtlı geliyor. Şimdi bu kısıtlamaları kaldıracağız. O halde tekrar Windows + R tuşlarına basarak çalıştırmayı açalım ve regedit yazalım. <br>
We solved the network, now let's do the same things to our system. In our system, it comes restricted for the same reasons. We will now remove these restrictions. So let's open run by pressing the Windows + R key again and type regedit. <br>
 
* şimdi bu konuma gidelim >>> Bilgisayar\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Session Manager\Memory Management <br>
* now let's go to this location >>> Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Session Manager\Memory Management  <br>
* ![tick2](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/ss1.png)<br><br>
* şimdi burada 4gb ram ve üzeri bilgisayarlar resimdeki değeri uygulasın <br>
* now here computers with 4gb of RAM and above apply the value in the picture <br> 
* ![newValue1](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/newValue1.png)<br><br>
* ![newValue1](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/newValue2.png)<br><br>
* Şimdiki işlem için biraz matematik yapacağız. <br>
* We're going to do a little math for the current operation. <br>
* mevcut RAM * 1024 * 1024 * 128  sonuç = 536.870.912 <br>
* Available RAM * 1024 * 1024 * 128 result = 536.870.912 <br> 
* Bu hesaptan sonra resimdeki işlemi yapabilirsiniz. <br> 
* After this account, you can do the action in the picture. <br>
* ![newValue3](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/newValue3.png)<br><br>
* şimdi bu konuma gidelim >>> Bilgisayar\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer <br>
* now let's go to this location >>> Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer <br>
* resimlerdeki değerleri eklemeye devam edin. <br>
* keep adding the values in the pictures. <br>
* ![newValue4](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/newValue4.png)<br><br>
* şimdi bu konuma gidelim >>> Bilgisayar\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\PriorityControl <br>
* now let's go to this location >>> Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\PriorityControl <br>
* resimlerdeki değerleri eklemeye devam edin. <br>
* keep adding the values in the pictures. <br>
* ![newValue5](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/newValue5.png)<br><br>
* şimdi bu konuma gidelim >>> Bilgisayar\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Dfrg\ <br>
* now let's go to this location >>> Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Dfrg\ <br>
* resimlerdeki değerleri eklemeye devam edin. <br>
* keep adding the values in the pictures. <br>
* ![newValue6](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/newValue6.png)<br><br>
* Şimdi komut satırını açalım ve "msconfig" yazalım. <br>
* Now let's open the command line and type "msconfig" <br>
* ![newValue7](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/newValue7.png)<br><br>
* resimdeki işlemleri sisteminize göre en yüksek yapın ve bilgisayarınızı yeniden başlatın <br>
* make the processes in the picture the highest according to your system and restart your computer <br>
* ![newValue8](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/newValue8.png)<br><br>
* şimdi yeni bir komut satırı açın ve bu komutu girin >>> Rundll32.exe advapi32.dll.ProcessIdleTasks <br>
* now open a new command line and enter this command >>> Rundll32.exe advapi32.dll.ProcessIdleTasks <br>
* ![newValue9](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/newValue9.png)<br><br>

## ===============================<br>
## evet, sistemimiz artık hem network hem de sistemsel olarak daha hızlı çalışacak. <br>
## yes, our system will now perform faster both network and systemically.
## ===============================<br>
# (Advanced security) İleri seviye güvenlik
Evet, biraz da güvenlikle ilgili işlemlerden bahsedelim <br>
Yes, let's talk about security-related transactions. <br>
## PAGEFILE <br>
* Tekrar Windows + R tuşlarına basarak çalıştır' açalım ve regedit yazalım. <br>
* Let's open run by pressing Windows + R keys again and type regedit. <br>
* Şimdi öncelikle pagefile diye bir şeyden bahsedeyim. pagefile aslında bu; RAM'den sarkan verilerin toplandığı yer diyebiliriz. Diğer bir deyişle, RAM'de yer kalmadığında veya çok meşgul olduğunda veriler yama dosyasına gider. Nitekim RAM'deki bazı uygulamaların hassas bilgileri yani şifreleri de bu dosyaya gider. Bu nedenle, bu verileri şifrelememiz gerekiyor. Aksi takdirde önemli ve hassas bilgilerimiz hacklenebilir. Bu yöntem adli bilişim sistemlerinde de kullanılmaktadır. Lafı fazla uzatmadan yama dosyamızı şifreleyelim. <br>
* Now, first of all, let me talk about something called pagefile. pagefile is actually this; We can say that it is the place where the data hanging from the RAM is collected. In other words, data goes to the patch file when RAM runs out or is too busy. As a matter of fact, sensitive information, namely passwords, of some applications in RAM also goes to this file. Therefore, we need to encrypt this data. Otherwise, our important and sensitive information can be hacked. This method is also used in forensic information systems. Without further ado, let's encrypt our patch file. <br> 
* şimdi bu konuma gidelim >>> Bilgisayar\HKEY_LOCAL_MACHINE\SYSTEM\ControlSet001\Policies <br>
* now let's go to this location >>> Computer\HKEY_LOCAL_MACHINE\SYSTEM\ControlSet001\Policies  <br>
* ![v1](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/v1.png)<br><br>
* NtfsEncryptPagingFile dosyasını bu şekilde ekleyip değerini 1 olarak belirlediğimizde artık şifreleme özelliğini açmış oluyoruz. Böylece uzaktan müdahalelerde daha fazla korunacağız. <br>
* When we add the NtfsEncryptPagingFile file in this way and set its value to 1, we now have the encrypt feature turned on. Thus, we will be more protected in remote interventions. <br>
* Şimdi başka bir işlem olarak bilgisayarımız kapandığında bu şifreleme dosyasının silinmesini sağlayalım. <br>
* Now, as another process, let's ensure that this encrypt file is deleted when our computer turns off. <br>
* şimdi bu konuma gidelim >>> Bilgisayar\HKEY_LOCAL_MACHINE\SYSTEM\ControlSet001\Control\Session Manager\Memory Management <br>
* now let's go to this location >>> Computer\HKEY_LOCAL_MACHINE\SYSTEM\ControlSet001\Control\Session Manager\Memory Management <br>
* resimlerdeki değerleri eklemeye devam edin. <br>
* keep adding the values in the pictures. <br>
* ![v2](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/v2.png)<br><br>
## SHARED FOLDERS <br>
* şimdi bu konuma gidelim >>> Bilgisayar\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\LanmanServer\Parameters <br>
* now let's go to this location >>> Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\LanmanServer\Parameters <br>
* resimlerdeki değerleri eklemeye devam edin. <br>
* keep adding the values in the pictures. <br>
* ![v3](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/v3.png)<br><br>
## REMOTE ACCESS DISABLE <br>
* şimdi bu konuma gidelim >>> Bilgisayar\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\RemoteRegistry <br>
* now let's go to this location >>> Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\RemoteRegistry <br>
* resimlerdeki değerleri eklemeye devam edin. <br>
* keep adding the values in the pictures. <br>
* ![v3](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/v4.png)<br><br>
## ===============================<br>
# (windows firewall) windows güvenlik duvarı
Şimdi Windows güvenlik duvarı hakkında bazı şeyler yapalım. <br>
Now let's do some things about Windows firewall. <br> 
* Şimdi önce komut satırını açalım ve "wf.msc" yazarak firewall'ı açalım. <br>
* Now let's open the command line first and open the firewall by typing "wf.msc". <br>
* Bize yapılacak dahili ve harici ping paketlerini bloklayalım. <br>
* Let's block the local and public ping packets that will be made to us. <br>
* ![vf1](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/wf1.png)<br><br>
* ![vf2](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/wf2.png)<br><br>
* ![vf3](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/wf3.png)<br><br>
* ![vf4](https://github.com/OgulcanKacarr/WindowsAdvancedSystemandNetworkAcceleration/blob/main/Images/wf4.png)<br><br>
## ===============================<br>
# (system problems) Sistem Sorunları
bilgisayarda herhangi bir sorun olup olmadığını ve çözülüp çözülmediğini görmek için komut satırı ekranına bu komutu girin; <br>
enter this command on the command line screen to see if there is any problem with the computer and if it is fixed; <br>
* "dism /online /cleanup-image /scanhealth" <br>
* ![cmd24](https://user-images.githubusercontent.com/63792003/122685788-3bd72100-d216-11eb-8a99-b4a15c7f88e5.png) <br> <br>
Sistemde bir hata varsa veya yoksa bu komutu kullanarak düzeltebiliriz. <br>
If there is an error in the system or not, we can use this command to fix it. <br>
* "sfc /scannow" <br>
* ![cmd24](https://user-images.githubusercontent.com/63792003/122685908-01ba4f00-d217-11eb-831f-e7168f6b69c4.png) <br> <br>

Eğer windows açılmıyorsa iso dosyası ile açtığınız cmd ekranına bu komutu giriniz. Sorununuz büyük ihtimalle çözülecektir. <br>
If windows does not open, enter this command on the cmd screen you opened with an iso file. Your problem will most likely be resolved. <br>
* "bootrec /fixmbr" <br>
* "bootrec /fixboot" <br>





