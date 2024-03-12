Hazim Khaled 

-Git Branches sind wie separate Pfade in einem Wald, auf denen verschiedene Entwicklungen gleichzeitig stattfinden können. Jeder Pfad repräsentiert eine andere Idee oder Funktion, die entwickelt wird, ohne die anderen zu beeinflussen. Zum Beispiel gibt es einen Hauptpfad, auf dem der stabile Code liegt, und separate Pfade für neue Funktionen, Fehlerkorrekturen oder Testversionen. Diese Branches ermöglichen es den Entwicklern, geordnet und effizient zu arbeiten, ohne dass Änderungen durcheinander geraten. 

 

- Merge: Beim Merge werden die Änderungen aus einem Branch in einen anderen zusammengeführt, um die Entwicklungsstränge zu vereinen. Wenn zwei Entwickler an unterschiedlichen Features arbeiten und ihre Änderungen in den Haupt-Branch integrieren möchten, wird der Merge verwendet, um die verschiedenen Versionen zu kombinieren. 

  

- Rebase: Rebase ermöglicht es, die Commit-Historie neu zu ordnen, indem Commits aus einem Branch auf einen anderen angewendet werden. Im Gegensatz zum Merge wird die Commit-Historie beim Rebase linearisiert, was dazu beiträgt, eine klarere und sauberere Historie zu erhalten. Dies kann helfen, Konflikte zu vermeiden und die Arbeit anderer Teammitglieder zu respektieren. 



 

- Cherry pick: Cherry picking bezieht sich auf die Auswahl bestimmter Commits aus einem Branch und deren Anwendung auf einen anderen. Wenn ein Entwickler nur bestimmte Änderungen aus einem Branch übernehmen möchte, anstatt den gesamten Branch zu mergen, kann er Cherry pick verwenden, um selektiv einzelne Commits auszuwählen und in einen anderen Branch zu übernehmen. 

  

- Reverse: Beim Reverse werden Änderungen rückgängig gemacht, entweder durch Umkehrung der Reihenfolge von Commits oder durch Zurücksetzen auf einen vorherigen Zustand. Dies kann nützlich sein, um Fehler zu beheben oder unerwünschte Änderungen rückgängig zu machen, indem man zu einem früheren Stand zurückkehrt. 

  

- Push: Beim Push werden lokale Commits auf einen entfernten Git-Server hochgeladen, um sie für andere Teammitglieder verfügbar zu machen. Dies ermöglicht es, die Arbeit mit anderen zu teilen und sicherzustellen, dass die Änderungen auf dem Server gesichert sind. 

  

- Fetch: Fetch lädt Änderungen und Updates vom entfernten Git-Server herunter, ohne jedoch automatisch lokale Dateien zu aktualisieren. Dadurch können Entwickler sehen, welche Änderungen auf dem Server vorhanden sind, ohne ihre lokalen Dateien zu beeinflussen. 



- Pull: Der Pull-Befehl kombiniert Fetch und Merge, indem er lokale Dateien mit den neuesten Änderungen vom entfernten Server aktualisiert. Es lädt zunächst die Änderungen vom Server herunter (Fetch) und führt dann einen Merge durch, um die heruntergeladenen Änderungen mit den lokalen Dateien zu kombinieren. 

  

- .gitignore-Datei: Die .gitignore-Datei wird verwendet, um bestimmte Dateien oder Verzeichnisse zu definieren, die von Git ignoriert werden sollen. Dies ist besonders nützlich für temporäre Dateien, Build-Ausgaben oder andere Dateien, die nicht versioniert werden sollen. Durch das Hinzufügen von Dateipfaden oder Muster in die .gitignore-Datei werden diese Dateien von Git beim Tracking ignoriert. 




  