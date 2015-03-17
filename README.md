# munin-plugins
Für Munin gibt es eine Reihe von clientseitigen Plugins,
die es möglich machen, verschiedene Dienste eines Servers (z.B. Datenbanken, CPU-Last, Mails, Sensoren, Netzwerk etc.) zu überwachen.
Diese Plugins werden von einem Daemon gestartet, der Anfragen des Munin-Masters über eine Netzwerkverbindung entgegennimmt.
Während der Daemon mit privilegierten Rechten (root) läuft, sorgt die Konfiguration dafür dass die Plugins mit eingeschränkten Rechten ausgeführt werden.

Die Entwicklung eigener Plugins ist mit grundlegenden Programmier-Kenntnissen möglich.

Die Plugins die du hier findest sind von mir entwickelt oder gefundene erweitert / umgeschrieben.

![nzbget_dl](http://nzbget.net/forum/download/file.php?id=413&mode=view "Munin-plugin nzbget_dl")
