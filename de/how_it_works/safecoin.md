#Safecoins

Safecoins können verdient, getauscht oder gekauft werden. Der Wert von safecoins wird durch den Markt festgelegt, durch eine Kombination aus Nachfrage und Angebot.

## Markt Preis

Die Anzahl an Safecoins im Umlauf erhöht sich mit steigender Nutzung des Netzwerk. Fast alle frühen Besitzer von Safecoins werden Farmer sein die mit dieser Bereitstellung von Resourcen sowohl Liquidität als auch Verteilung Vermögen erzeugen. Es wird davon ausgegangen das fast alle Benutzer mindestens ein paar Safecoins in ihrer Geldbörse haben werden.

Benutzer können ihre Safecoins gegen Dienste im Netzwerk, Geld (oder andere digitale Währungen) tauschen in dem sie eine Börse benutzen. Der Anteil an Safecoins die gespeichert werden (in neuen Geldbörsen) gegenüber dem Anteil der Farmern zugeteilt wird bestimmt den Preispunkt. Dieser Preispunkt wird den Marktwert von Safecoins festlegen.



## Resourcen und Währung

Safecoins werden genutzt um Zugang zu Services im SAFE Netzwerk zu erhalten. Das fördert eine konstante Wiederverwendung was in einer gesteigerten Nachfrage nach einer endlichen Resource resultiert was dazu führt das der Wert der Safecoins mit der Zeit steigt. Während die Safecoins ansich im Wert steigen, steigt auch die Zahl der Netzwerk Dienste (Resourcen) die sie kaufen. Siehe dazu Bild 2.


![](safecoin resources.png)

## Farming Raten

Farming ist ein Prozess bei dem Benutzer dem Netzwerk Resourcen (Festplattenplatz, Prozessor und Bandbreite) bereistellen.

Wie in Bild 1 zu sehen, basiert der Safecoin Verdienst Algorithmus auf der Sigmoid Kurve insofern das alle Vaults verdienen, zuerst langsam. Die Rate steigt wenn der Farmer mehr in Richtung Netzwerk Durchschnitt speichert. Die Verdienst Rate berücksichtigt ausserdem den Rang des Vaults, ein Prozess bei dem das Netzwerk die Nützlichkeit jede Node von 0 (schlechteste) bis 1 (beste) bewertet. Die Safecoin Farming Rate ist letztlich das Result der Netzwerk Rate, die Balance zwischen Angebot und Nachfrage im Netzwerk, multipliziert mit dem Rang des Vaults.  Die Netzwerk Rate wird sich bei 20$ prozent über Durchschnitt anfangen auszugleichen und damit riesige Vaults entmutigen welche Zentralisierung in den Farming Prozess würden. Safecoin wird ihnen vom Netzwerk zugeteilt und wird den erfolgreichen Nodes ausgezahlt wenn Daten von ihnen abgerufen werden (GETS), im Gegensatz dazu, wenn Daten gespeichert werden (PUTS).


![](safecoin farming speed.png)

Das Netzwerk erhöht die farming Vergütung wenn Platz erfoderloch ist und senkt ihn wenn Platz im Überfluss vorhanden ist. Daten sind gleichmäßig über das Netzwerk verteilt, daher sollten Farmer die ihren Verdienst maximieren wollen mehrere durchschnittliche Nodes betreiben anstatt einer hoch performanenten Node.


## Safecoin Transfer Mechanismus
Im Gegensatz zu bitcoin nutzt das SAFE Netzwerk keine blockchain um den Besitz der safecoins verwalten. Die Transaction Manager des SAFE Netzwerk sind entgegengesetzt; unverkettet, was bedeutet das lediglich der letzte und der aktuelle Besitzer bekannt sind. In dieser Hinsicht ist es sinnvoll Safecoins wie digitales Bargeld zu betrachten.

Eines der größten Probleme jeder virtuellen Währung ist es das Problem der doppelten Ausgabe (double spending) zu verhindern. Innerhalb des SAFE Netzwerk ist der Transfer von Daten, inklusive Safecoin, atomar, unter Verwendung einer kryptographischen Signatur um den Besitz zu übertragen.

Safecoin, die Währung des SAFE Netzwerk wird in Relation zur Netzwerk Nutzung generiert. Wenn Daten gespeichert werden, oder Programme erstellt und genutzt werden, generiert das Netzwerk Safecoins, jedes mit seiner eigenen ID. Da diese Coins teilbar sind erhält jede Stückelung eine neue und komplett eindeutige ID.

Wenn das Netzwerk den Benutzern Safecoins zuweist, kann nur dieser spezielle Benutzer den Besitz mit Hilfe der kryptographischen Signatur übertragen. Für illustrative Zwecke, wenn Alice mit dem Client einen Safecoin an Bob bezahlt reicht sie einen Zahlungsanfrage ein. Der Transaction Manager überprüft ob Alice der derzeitge Besitzer der Safecoin ist indem er ihre öffentlichen Schlüssel heranzieht und bestätigt das sie von dem richtigen und korrespondieren privaten Schlüssel signiert wurde. Der Transaction Manager akzeptiert nur eine signierte Nachricht vom existierenden Besitzer. Das belegt zweifelsfrei das Alice der Besitzer der safecoin ist und der Besitz dieser speziellen Safecoin wird an Bob übertragen. Von nun an ist lediglich Bob dazu in der Lage die Safecoin an einen anderen Besitzer zu übertragen. Dieser Prozess ist in Bild 3 dargestellt.

As the coins are allocated to users by the network, only that specific user can transfer ownership of that coin by cryptographic signature. For illustrative purposes, when Alice pays a coin to Bob via the client, she submits a payment request. The Transaction Managers check that Alice is the current owner of the coin by retrieving her public key and confirming that it has been signed by the correct and corresponding private key. The Transaction Managers will only accept a signed message from the existing owner. This proves beyond doubt that Alice is the owner of the coin and the ownership of that specific coin is then transferred to Bob and now only Bob is able to transfer that coin to another user.This process is highlighted in figure 3.

![](safecoin transfer mech.png)



