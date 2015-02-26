# Vaults
Das SAFE Netzwerk besteht aus Software Prozessen (nodes) welche als Vaults bekannt sind. Jeder Vault befindet sich auf der Festplatte des Benutzers und erfüllt mehrere Aufgaben, spezialisiert auf das Netzwerk und mit der Fähigkeit sich anzupassen. Eine seiner Hauptaufgaben ist das Speichern von verschlüsselten Daten das ihm von anderen Vaults im Netzwerk zugeteilt wurde.

Eine weitere Funktion oder Rolle eines Vaults ist das Verwalten von anderen Vaults. In dem Moment in dem Datenteile zwischen den Vaults verteilt werden, beobachtet und überwacht der Manager Teil des Vaults die Datenintegrität.

Vaults können zusätzlich eine Transaktions Manager oder Transaktions Validierungs Rolle haben.

Die Vaults wissen nichts über den eigentlichen Inhalt der Daten die sie speichern (diese können nur durch den SAFE client entschlüsselt werden). Weil die gespeicherten Daten lediglich einen kleinen Teil darstellen, ist es nicht möglich zu dechiffrieren was die eigentliche Quelle der Daten war, z.b. ein Dokument oder Kommunikation.

Für jeden Vault der Daten vorhält gibt es weitere einundreissig Vaults die dieselben Daten speichern. Das bedeutet das sobald ein Vault offline geht oder ein Datenteil als korrupt erkannt wird, die Daten nicht verloren gehen. Jeder Vault findet automatisch weitere Vaults um die Daten zu speichern.

Vaults sind für die Benutzer das SAFE Netzwerk nicht sichtbar. Stattdessen sieht der Benutzer lediglich eine virtuelle Festplatte die in seinem Computer eingebunden wird. Durch die konstante Kommunikation und Überwachung der Vaults untereinander, erfolgt der Zugriff auf die Daten durch den Benutzer unmittelbar.
