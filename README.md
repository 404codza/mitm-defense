# mitm-defense
mitm saldırılarına karşı bilgilendirme uygulaması


Nasıl KUllanılır?

1-cmd aç

2-cd "hangi dosyada ise"/mitm-defense-main

3-codzamitm.py

-uygulama haline getirme 
-mitm-defense-main>python -m PyInstaller --onefile codzamitm.py

-winpcap programını yüklemelisiniz.
-Windows için bir kütüphanedir ve programların ağ paketlerini yakalamasına ve göndermesine izin verir. 
Bu, işletim sisteminin ağ yığını tarafından sağlanan düşük seviyeli paket yakalama mekanizmalarına yüksek seviyeli bir arayüz sağlar. 
WinPcap, ağ analizi ve ağ izleme yazılımları gibi yaygın olarak, 
ayrıca güvenlikle ilgili yazılımlar ve saldırı algılama sistemleri gibi kullanılır.
Bu, belirli bir ağ arayüzünden ağ trafiğini yakalamak, 
paketleri çeşitli kriterlere göre filtrelemek ve daha sonra yakalanan paketleri işlemek veya analiz etmek için kullanılabilir.
