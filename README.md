ircpanel
========

2007 yılında yazdığım ve unreal benzeri panelleri sanal olarak çalıştıran ve yöneten bir panel ve satış uygulaması... Serbestçe kullanabilirsiniz...<br>
<br>
Örnek ekran görüntüleri:<br>
<br>
<img src="http://www.grinet.com.tr/vshell_2358461505.png" alt=""><br>
<br>
<br>
Çalıştırılan servisler bu şekilde gözükür:<br>
------------------------------------------<br>

<code>
apache    4088  0.0  0.4  4248 2308 ?        S    03:37   0:00 /var/www/html/panel/progs/unreal/src/ircd -h /var/www/html/panel/progs/unreal/_customer_servers/000135_z2rDsuf36QMIXgf2/unrealircd.conf
apache    4105  0.8  0.5  7896 2992 ?        S    03:38   0:00 ../../services -dir /var/www/html/panel/progs/anope_services/_customer_servers/000075_5Z8wUN0cke8aRoIk -log services.log
apache    4114  1.5  0.3 36808 1796 ?        Sl   03:38   0:00 /var/www/html/panel/progs/shoutcast/sc_serv /var/www/html/panel/progs/shoutcast/_customer_servers/000017_z8zpJfy0J9Sv8GeH/sc_serv.conf
apache    4132  1.7  0.3 37224 1800 ?        Sl   03:38   0:00 /var/www/html/panel/progs/shoutcast/sc_serv /var/www/html/panel/progs/shoutcast/_customer_servers/000016_HT88jxG3PejW8Qei/sc_serv.conf
</code>
