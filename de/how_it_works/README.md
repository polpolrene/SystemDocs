# Wie es funktioniert.

Wenn ein Benutzer den SAFE client herunterlädt und installiert wird ein Vault auf seinem Computer konfiguriert.

Nach dem Beitritt und Anmelden am SAFE Netzwerk sieht der Benutzer ein virtuell eingebunde Festplatte in seinem System. Diese Festplatte zeigt die statischen Daten an die verschlüsselt und verteilt auf den anderen Vaults liegen.

Der Vault des Benutzers kann ausserdem dynmische Daten wie z.B Kommunikation über VoIP handhaben.

Die Daten werden vor der Speicherung im SAFE Netzwerk automatisch verschlüsselt. Dieser Selbstverschlüsselungsprozess besteht aus dem Aufteilen der Daten in kleine Teile und anschliessendem Verschlüsseln dieser Teile mit den Anmeldedaten des Benutzers und den Daten selbst. Das bedeutet das für eine Entschlüsselung der Daten durch Dritte, diese die sicheren Anmeldedaten des Benutzers und Wissen über den speziellen Datenteil haben müssten. Keine dieser Informationen liegt auf Systemen oder Servern von Drittanbietern.

Typischerweise verbindet sich ein Benutzer zum Netzwerk durch einen Router. Der Router verwendet das "Reliable UDP (RUDP) Protocol" um sich zum Netzwerk zu verbinden. RUDP ist ein stabilieres Protokoll als UDP da verlorene Pakete noch einmal gesendet werden und es im Gegensatz zu TCP im Stande ist NAT Router zu durchqueren. Die Verwendung von RUDP im SAFE Netzwerk erlaubt es Daten durch Router zu fliessen ohne dabei korrumpiert oder abgefangen zu werden.

Der Vault des Benutzers verbindet sich zu anderen Vaults als Teil des speichern und verwalten von Daten. Die Vaults werden konstant anhand der folgenden Kritieren überprüft und klassifiziert (durch die Datenhaltungsverwaltung)

* **Verfügbarkeint** - Wie oft der Vault an oder aus ist.
* **Speicher** - Wieviel Speicher im Vault ist
* **CPU** - Wieviele CPU resource der Vault hat
* **Bandbreite** - Wie schnell oder langsam der Zugang zum Vault ist

Wenn Bedarf und Verfügbarkeit von Resourcen sich im SAFE Netzwerk verändern passt der Vault sich dementsprechend an und gleicht die Last im Netzwerk konstant aus. Dieser Anpassungsprozess wird automatisch durch die Vaults  erledigt. Da das SAFE Netzwerk komplett autonom arbeitet, kann es sehr schnell und ohne die Hilfe von menschlicher Hand reagieren.

Wenn ein Benutzer mehr Speicherlatz zur Verfügung stellt als er selber benötigt, so wird er nach dem Zufallsprinzip mit safecoins dafür belohnt. Safecoins sind notwendig um Zugang zum Netzwerk zu erhalten. Wieviele safecoins ein Benutzer hat, kann er durch einen Black auf seine Geldbörse erfahren. Die Geldbörse wird automatisch im Zuge der SAFE Client Installation und des Anmeldeprozesses angelegt.

Programm Entwickler verdienen safecoins wenn sie Programme für das SAFE Netzwerk entwicklen. Sobald die Programme genutzt werden, verdient der Entwickler damit safecoins.

Entwickler des SAFE Netzwerk können ebenfalls safecoins verdienen in dem sie zu Code des SAFE Netzwerk beitragen.
