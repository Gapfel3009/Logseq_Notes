- Vollbackup
	- Ein Vollbackup ist eine Datensicherung des Vollständigen Systems
- inkrementelles Backup
	- Ein inkrementelles Backup ist eine Datensicherung die nur neuen Daten auf dem System speichert.
- Differenzielles Backup
	- Ein Differenzielles Backup ist eine Datensicherung die nur die neuen Daten auf dem System speichert die seit dem letzten __Vollbackup__ entstanden sind.
-
- ||Backupdauer|Speicherbedarf| Wiederherstellungsdauer|Verwaltungskomplexität|
  |Vollbackup|Langsam|hoch|schnell|einfach|
  |Inkrementelles Backup|schnell|niedrig|langsam| Komplex|
  |Differentielles Backup|mittel|mittel|mittel|mittel|
- ||Vorteil|Nachteil|
  |Vollbackup|Einfach zu verwalten / Wiederherstellung einfach|Viel Speicherplatz / Dauert lange|
  |Inkrementelles Backup|Wenig Speicher / schnelle Backupdauer|Wiederherstellung dauert länger / Komplexe Verwaltung|
  |Differentielles Backup| Schnelle Wiederherstellung|Dauert länger / Speicherplatz|