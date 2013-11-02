ircpanel
========

2007 yılında yazdığım ve unreal benzeri panelleri sanal olarak çalıştıran ve yöneten bir panel ve satış uygulaması... Serbestçe kullanabilirsiniz...<br>
<br>
Örnek ekran görüntüleri:<br>
<br>

<img src="http://www.grinet.com.tr/vshell_snaps/vshell_panel_giris.png" alt=""><br>
<img src="http://www.grinet.com.tr/vshell_snaps/vshell_panel_ornek.png" alt=""><br>
<img src="http://www.grinet.com.tr/vshell_snaps/vshell_panel_ornek_2.png" alt=""><br>
<img src="http://www.grinet.com.tr/vshell_snaps/vshell_panel_ornek_3.png" alt=""><br>
<img src="http://www.grinet.com.tr/vshell_snaps/vshell_yeni_sunucu_ekleme.png" alt=""><br>

<br>
<br>
Çalıştırılan servisler bu şekilde gözükür:<br>
------------------------------------------<br>
<pre>
apache    4088  0.0  0.4  4248 2308 ?        S    03:37   0:00 /var/www/html/panel/progs/unreal/src/ircd -h /var/www/html/panel/progs/unreal/_customer_servers/000135_z2rDsuf36QMIXgf2/unrealircd.conf
apache    4105  0.8  0.5  7896 2992 ?        S    03:38   0:00 ../../services -dir /var/www/html/panel/progs/anope_services/_customer_servers/000075_5Z8wUN0cke8aRoIk -log services.log
apache    4114  1.5  0.3 36808 1796 ?        Sl   03:38   0:00 /var/www/html/panel/progs/shoutcast/sc_serv /var/www/html/panel/progs/shoutcast/_customer_servers/000017_z8zpJfy0J9Sv8GeH/sc_serv.conf
apache    4132  1.7  0.3 37224 1800 ?        Sl   03:38   0:00 /var/www/html/panel/progs/shoutcast/sc_serv /var/www/html/panel/progs/shoutcast/_customer_servers/000016_HT88jxG3PejW8Qei/sc_serv.conf
</pre>

<pre>Örnek Log :
-----------
// 000136 Numarali Unreal Sunucu icin Log Dosyasi


[Sun Jul 8 07:09:29 2007] - SERVER services.irc2.oxio.net
[Sun Jul 8 07:09:29 2007] - Permanent Global Q:line added for NickServ on Sun Jul 8 04:09:29 2007 GMT (from services.irc2.oxio.net: Reserved for services)
[Sun Jul 8 07:09:29 2007] - Permanent Global Q:line added for ChanServ on Sun Jul 8 04:09:29 2007 GMT (from services.irc2.oxio.net: Reserved for services)
[Sun Jul 8 07:09:29 2007] - Permanent Global Q:line added for HostServ on Sun Jul 8 04:09:29 2007 GMT (from services.irc2.oxio.net: Reserved for services)
[Sun Jul 8 07:09:29 2007] - Permanent Global Q:line added for MemoServ on Sun Jul 8 04:09:29 2007 GMT (from services.irc2.oxio.net: Reserved for services)
[Sun Jul 8 07:09:29 2007] - Permanent Global Q:line added for BotServ on Sun Jul 8 04:09:29 2007 GMT (from services.irc2.oxio.net: Reserved for services)
[Sun Jul 8 07:09:29 2007] - Permanent Global Q:line added for HelpServ on Sun Jul 8 04:09:29 2007 GMT (from services.irc2.oxio.net: Reserved for services)
[Sun Jul 8 07:09:29 2007] - Permanent Global Q:line added for OperServ on Sun Jul 8 04:09:29 2007 GMT (from services.irc2.oxio.net: Reserved for services)
[Sun Jul 8 07:09:29 2007] - Permanent Global Q:line added for Global on Sun Jul 8 04:09:29 2007 GMT (from services.irc2.oxio.net: Reserved for services)
[Sun Jul 8 07:10:55 2007] - Error binding stream socket to IP 192.168.8.119 port 5998 - irc2.oxio.net[]:Cannot assign requested address
[Sun Jul 8 08:34:10 2007] - Error binding stream socket to IP 192.168.8.119 port 5998 - irc2.oxio.net[]:Cannot assign requested address
[Sun Jul 8 08:35:20 2007] - SERVER services.irc2.oxio.net
[Sun Jul 8 08:35:20 2007] - Permanent Global Q:line added for NickServ on Sun Jul 8 05:35:20 2007 GMT (from services.irc2.oxio.net: Reserved for services)
[Sun Jul 8 08:35:20 2007] - Permanent Global Q:line added for ChanServ on Sun Jul 8 05:35:20 2007 GMT (from services.irc2.oxio.net: Reserved for services)
[Sun Jul 8 08:35:20 2007] - Permanent Global Q:line added for HostServ on Sun Jul 8 05:35:20 2007 GMT (from services.irc2.oxio.net: Reserved for services)
[Sun Jul 8 08:35:20 2007] - Permanent Global Q:line added for MemoServ on Sun Jul 8 05:35:20 2007 GMT (from services.irc2.oxio.net: Reserved for services)
[Sun Jul 8 08:35:20 2007] - Permanent Global Q:line added for BotServ on Sun Jul 8 05:35:20 2007 GMT (from services.irc2.oxio.net: Reserved for services)
[Sun Jul 8 08:35:20 2007] - Permanent Global Q:line added for HelpServ on Sun Jul 8 05:35:20 2007 GMT (from services.irc2.oxio.net: Reserved for services)
[Sun Jul 8 08:35:20 2007] - Permanent Global Q:line added for OperServ on Sun Jul 8 05:35:20 2007 GMT (from services.irc2.oxio.net: Reserved for services)
[Sun Jul 8 08:35:20 2007] - Permanent Global Q:line added for Global on Sun Jul 8 05:35:20 2007 GMT (from services.irc2.oxio.net: Reserved for services)
[Fri Dec 21 02:19:24 2007] - error binding to local port for stats.irc2.oxio.net[192.168.11.107]:Cannot assign requested address
[Fri Dec 21 02:20:44 2007] - SQUIT services.irc2.oxio.net (Ping timeout)
</pre>
