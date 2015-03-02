# Geboortedatum Paradox/Sybil aanval

##Aanval beschrijving
Met dit aanval, overspoelt een aanvaller het netwerk met kluizen waarover men controle heeft, door een kluis te omringen met 3 of meerdere kwaadaardige kluizen om controle uit te oefenen over dat kluis. 

##Aanvals doel

In zo'n scenario, kan een aanvaller verwijdering van data snippertjes verzoeken door als data managers te fungeren over het onder controle genomen kluis. Dit zorgt dat de Data houders het snippertje verwijderen als reactie op wat een legitieme verzoek lijkt en voorkomt toegang tot dat data door een legitieme gebruiker. 

Terwijl het niet mogelijk is opzettelijk kwaadaardige kluizen te positioneren binnen een bepaald punt in het SAFE Netwerk, met ongeveer 0.8% van de kluizen in het netwerk onder (tijdelijke) controle van een aanvaller, is het mogelijk dat de aanvaller in ieder geval 1 kluis omringd op het SAFE netwerk, waardoor men controle kan uitoefenen op die kluis en quorum kan bereiken onder valse acties.


##Aanval ontwijking

Het SAFE Netwerk vereist dat alle verzoeken verwerkt worden door twee groepen van kluizen. 

Een Maidsafe client geeft een verzoek aan 4 Data managers, die verifiëren het verzoek gebaseerd op een client's handtekening. Het verzoek wordt doorgegeven aan gedetermineerd geselecteerde groep van 4 kluizen, die verifiëren of het verzoek is gebaseerd op de client's handtekening. 

Door gedetermineerd selecteren van het tweede groep Data managers, is dit aanval niet meer waar voor het SAFE Netwerk, gezien een aanvaller geen controle kan krijgen over een kluis, door deze te omringen.  

Om dit te omzeilen, zou de aanvaller de mogelijkheid moeten hebben om specifieke kluizen te omringen in het SAFE Netwerk. Dit kan niet bereikt worden, omdat van een aanvaller is vereist dat men effectief verschillende waarde genereert, die gehasht met SHA-512, resulteren in een gesloten hashes rond om 1 bepaalde punt.
