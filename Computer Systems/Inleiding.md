# Inleiding
## Inhoudsopgave
- ### [Computer vs Embedded System](#Computer-vs-embedded-system)
- ### [Hedendaagse technologie](#hedendaagse-technologie)
- ### [Digitale elektronica](#digitale-elektronica)
- ### [Analoog vs digitaal](#analoog-vs-digitaal)
- ### [Waarom digitale elektronica](#waarom-digitale-elektronica)
- ### [Experimentele technologieën](#experimentele-technologieën)

***

## Computer vs Embedded System

### **Computer** : 
- #### **multifunctioneel** : we kunnen er verschillende zaken mee uitvoeren
- #### **programmeerbaar** : we kunnen het toestel programmeren zodat het multifunctioneel wordt
- #### **digitaal** : we werken met discrete waarden (0 en 1)
- #### **elektronisch** : het toestel werkt op spanning waarbij er stroom vloeit doorheen de componenten waaruit deze bestaat

### **Embedded Systeem**
= Een computer die deel uitmaakt van een (groter) toestel.  
Het toestel heeft een specifieke functie die verbonden is met het toestel waarin het is ingebouwd.

***

## Hedendaagse Technologie
Digitale elektronica -> dominant vandaag de dag

### Machine van Babbage (**mechanische computer**)
- Centraal staat dat berekeningen herhaaldelijk, automatisch en zonder fouten kunnen worden uitgevoerd.
- Programmeerbaar
- Ontworpen / Beschikte niet over de onderdelen om de machine te maken

***

## Digitale elektronica
#### **Elektronica** : Technologie die gebruik maakt van elektrische signalen om informatie en/of energie te verwerken
#### **Digitaal** : Maakt gebruik van discrete, discontinue waarden
#### **Binair** : Maakt gebruik van slecht twee waarden

### 3 soorten
#### **Digitale elektronica** : Verwerkt informatie op een digitale, binaire manier
#### **Analoge elektronica** : Verwerkt informatie op een analoge manier
#### **Vermogen elektronica** : verwerkt geen informatie maar energie en vermogen

***

## Analoog vs Digitaal
#### **Analoog** : Elke spannings- of stroomwaarde tussen twee grenzen heeft een betekenis
#### **Digitaal** : Slects twee waarden zijn geldig, namenlijk 0 en 1.

***

## Waarom digitale elektronica
#### **Kwaliteit** : 
- Stabiel in de tijd en bij bewerkingen of versturen
- Zelf kiezen (trade-off met opslagruimte)
- Verschillende kwaliteiten op hetzelfde toestel

#### **Productieprijs** : 
Digitale schakelingen zijn eenvoudiger en lenen zich gemakkelijker tot hoge integratie op IC (Integrated Circuit)

#### **Dezelfde hardware** : 
kan gebruikt worden voor verschillende informatie (beeld, geluid, tekst,...)

#### **Redundantie, encryptie en compressie** :
- **Redundantie** : we voegen extra informatie (extra bits) toe om de informatie beter bestand te maken tegen fouten.
> **! LET OP** | Deze extra informatie heeft dus een doel en is **NIET** overbodig

- **Encryptie** :
We vervormen de informatie zodat deze onleesbaar wordt voor derden. Enkel de beoogde ontvangen kan met de juiste sleutels de informatie lezen.

- **Compressie** : 
Dit is het tegenovergestelde van redundantie. We verwijderen geheel of gedeeltelijk redundantie informatie, niet omdat deze overbodig is, maar om opslagruimte / bandbreedte/... te besparen.

#### **Redelijk betrouwbaar** :
Digitale hardware is niet altijd even betrouwbaar. Veel hangt af ven het ontwerp

#### **Klein** : 
Zoals eerder aangehaald, is digitale elektronica door miniaturisatie klein en draagbaar.

***

## Experimentele technologieën

### Optische technologie
- Gebruiken photonen (licht-deeltjes), geproduceerd door lasers of diodes, als informatiedragers ipv. elektronen in de huidige computers.

#### **+ :** hogere bandbreedtes, senller, minder warmteproductie, verbruikt minder energie.
**- :** Nog niet alle elektrische componenten kunnen omgezet worden naar optische componenten -> tijdelijke tussenstap: hybride systemen.

### Kwantumtechnologie
- Maken gebruik van de quantum-mechanische effecten van elementaire deeltjes, genaamd kwantumdeeltjes. Het geheugen van een kwantumcomputer bestaat uit qubits waarbij elk qubit tegelijkertijd de waarden 0 en 1 heeft.

**+ :** Berekeningen worden veel sneller uitgevoerd op grotere hoeveelheden data -> kan ingezet worden voor wetenschappelijk onderzoek waarbij intensieve simulaties uitgevoerd moeten worden.

**- :** Er is heel wat nodig (bv. extreme koeling) om een kwantumcomputer stabiel te houden, algoritmen moeten aangepast worden om parallel ipv. serieel uitgevoerd te kunnen worden.