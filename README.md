# Linux Basiswissen 

## Agenda 

  1. Distributionen 
     * [Überblick](overview-distros.md)
  1. Verzeichnisse und Dateitypen 
     * [Verzeichnisaufbau](verzeichnisaufbau.md)
     * [Dateitypen](dateitypen.md) 
  1. Basisbefehle
     * [In den Root-Benutzer wechseln - sudo](sudo.md)  
     * [Wo bin ich ?](pwd.md)
     * [Praktische Ausgabe von langen Seiten - less](less.md) 
     * [Datei anlegen - touch](touch.md)
     * [Autovervollständigen * und tab-Taste](autocomplete.md) 
     * [Welches Programm wird verwendet](which.md)
  1. Erweiterte Befehle (Nice to have) 
     * [Alias Befehle anzeigen](alias.md)
     * [Welche Bibliotheken verwendet ein ausführbares Programm](ldd.md)
  1. Dateien und Verzeichnisse
     * [Mit cd im System navigieren](cd.md)
     * [Verzeichnisse in Listenansicht mit versteckten Dateien anzeigen -> ls -la](list.md)
     * [Inhalt in Datei schreiben und anhängen](file-write-append.md)
     * [Verzeichnisse anlegen](mkdir.md)
     * [Verzeichnisse und Dateien löschen](file-dir-delete.md)
     * [Kopieren/Verschieben/Umbenennen von Dateien und Files](file-rename-copy-mv.md) 
     * [Arbeiten mit vi](vi.md)
    
  1. Prozesse 
     * [Prozesse anzeigen - ps/pstree -p](prozesse.md)
     * [Prioritäten und NiceNess](nice-pr.md)
  1. Benutzer, Gruppen und Rechte 
     * [Rechte](rechte.md) 
     * [Dateien für Benutzer und Gruppen](files-users-groups.md) 
     * [Benutzer anlegen](create-users.md) 
     * [Benutzer löschen (debian)](deluser.md)
     * [sudo Benutzer erstellen](mod-user-sudo.md) 
  1. Dateimanipulation/Unix Tools
     * [Anfang oder Ende einer Datei/Ausgabe anzeigen](head-tail.md)
     * [cat/head/tail-Beginn/Ende einer Datei anzeigen](cat-head.md)
     * [zcat - Inhalte einer mit gzip komprimierten Datei anzeigen](zcat.md)
     * [wc - Zeilen zählen](wc.md)
     * [Bestimmte Zeilen aus Datei anzeigen - grep](grep.md)
     * [Erweiterte Suche mit Grep](grep-extended.md)
     * [Finden von files nach Kriterien - find](find.md)
  1. Logs/Loganalyse
     * [Logfile beobachten](tailf.md)
     * [Dienste debuggen](debug-service.md)
     * [Rsyslog](rsyslog.md)
     * [Journal analysieren](journalctl.md) 
  1. Bash: Variablen, Kommandosubstitution und Quotes 
     * [Kommandos ausgeben und weiter verwenden](command-substitution.md)
     * [Setzen und verwenden von Variablen](variables.md)
     * [Quoting](quoting.md) 
  1. Dienste/Runlevel(Targets verwalten) 
     * [Systemd Überblick](/systemd.md) 
     * [Die wichtigsten systemctl/service](systemctl-service.md)
     * [Systemctl - timers](systemctl-timers.md)
     * [Gegenüberstellung service etc/init.d/ systemctl](service-initd-systemctl.md)
  1. Partitionierung und Filesystem
     * [parted and mkfs.ext4](parted-mkfs.md)
  1. Boot-Prozess und Kernel 
     * [Hintergründe zum Starten des Systems](/starten-des-system.md)
     * [Grub konfigurieren](grub.md)
     * [Kernel Params beim Booten übergeben](/kernel-params.md)
     * [Kernel-Version anzeigen](kernel-version.md) 
     * [Kernel-Module laden/entladen/zeigen](kernel-modules.md) 
  1. Hilfe 
     * [Hilfe zu Befehlen](help.md)
  1. Grafische Oberfläche und Installation 
     * [Gnome unter Ubuntu installieren](gnome-ubuntu.md) 
     * [X-Server - Ausgabe auf Windows umleiten](xserver-windows-client.md)
     * [Installations-Images-Server](https://ubuntu.com/download/server#download) 
  1. Wartung, Sicherung und Aktualisierung
     * [Aktualisierung des Systems](update-upgrade.md)
     * [Paketmanager apt/dpkg](apt-dpkg.md) 
     * [Archive runterladen und entpacken](tar-download.md) 
     * [Mehrere Versionen eines Programms z.B. php (cli) verwalten](update-alternatives.md)
     * [Verzeichnisse in archiven sichern - tar](/backups/tar.md)
  1. Firewall und ports
     * [ufw (uncomplicated firewall)](ufw.md)
     * [firewalld](firewalld.md)
     * [Scannen und Überprüfen mit telnet/nmap](nmap-telnet.md) 
  1. Netzwerk/Dienste 
     * [IP-Adresse von DHCP-Server holen (quick-and-dirty)](dhclient.md) 
     * [Auf welchen Ports lauscht mein Server - lsof](lsof.md) 
     * [Hostname setzen](hostnamectl.md)
  1. Tools/Verschiedens 
     * [Remote Desktop für Linux / durch Teilnehmer getestet](https://wiki.ubuntuusers.de/Remmina/)
     * [Warum umask 002 und 0002 ? - Geschichte](umask-002-022-why.md)
     * [lokale Mails installieren](local-mail.md)
     * [Debian/Ubuntu - deb - Paket entpacken](deb-unboxing.md)
     * [Geänderte Dateien zu anderem Server schicken](rsync.md)
  1. Bash/Bash-Scripting 
     * [Einfaches Script zur Datumsausgabe](script-date.md) 
     * [Ausführen/Verketten von mehreren Befehlen](multiple-commands.md)
  1. Timers/cronjobs 
     * [Cronjob - hourly einrichten](cronjob-hourly.md)
     * [cronjob (zentral) - crond](crond.md) 
  1. Übungen 
     * [Übung Verzeichnis](/uebungen/uebung1-verzeichnisse-anlegen.md)
     * [Übung Dienste](/uebungen/uebung2-dienste.md) 
     * [Übung Umleitung mit Variable](uebung3-umleitung-mit-variable.md) 
     * [Übung user/password](uebung4-user-and-password-change.md)
  1. Literatur 
     * [Literatur](literatur.md) 
     * [Cheatsheet Commandline](https://cheatography.com/davechild/cheat-sheets/linux-command-line/pdf/)
     * [Wo finde ich Hilfe im Internet](hilfe-im-internet.md)



