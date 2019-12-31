**Strategie**
Ich habe ein NAS mit einer NFS-Freigabe Backup. Hier haben die zu sichernden Host's ein Verzeichnis mit ihren Namen.
In diesen Verzeichniss speichern Sie ihre Backups. Was und wie Gesichert wird ist für jeden Host indivituell. 
Die Backups von Fileserver und Desktop syncronisiert mein NAS mit meinen Onlinspeicher.

Erstellt wird das Backup mit cron. Der Sync erfolgt auch Zeitgesteuert nachdem alle Backups abgeschlossen sind.

Vor kurzen habe ich ein Tool endeckt das alla meine Ideen vereint:
https://restic.readthedocs.io/en/latest/index.html 

