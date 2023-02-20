Je hebt nodig:

+ Een Raspberry Pi Pico
+ Een potentiometer
+ 3 x bus-bus verbindingsdraden

Een **potentiometer** heeft drie pinnen:
- Aarde
- Analoog signaal
- 3V3 (vermogen)

Als de potentiometer helemaal naar **links** is gedraaid, wijst de pijl naar de **GND** -pin, als hij helemaal naar **rechts**is gedraaid, wijst de pijl naar de **3V3** -pin. De middelste pin is de pin waaruit de Raspberry Pi Pico een waarde leest.

![Een illustratie van een potentiometer.](images/potentiometer-illustration.png){:width="400px"}

**Aansluiten:** Zoek drie bus-bus verbindingsdraden en bevestig er één aan elk been van de potentiometer. Je kunt de benen met wat isolatietape vastzetten als ze los voelen.

Sluit het andere uiteinde van elke verbindingsdraad aan op de Raspberry Pi Pico:

+ Sluit de draad die gemarkeerd is met een kleine 1 aan op de **GND** pin tussen **GP21** en **GP22**.
+ Verbind de middelste pin met de **GP26_A0** pin. Dit is een analoge pin.
+ Verbind de pin gemarkeerd met een kleine '3' met de **3V3** pin.

![Een potentiometer aangesloten op een Raspberry Pi Pico.](images/pot-diagram.png)

***
Dit project werd vertaald door vrijwilligers:

[name]

[name]

[name]

Dankzij vrijwilligers kunnen we mensen over de hele wereld de kans geven om in hun eigen taal te leren. Jij kunt ons helpen meer mensen te bereiken door vrijwillig te starten met vertalen - meer informatie op [rpf.io/translate](https://rpf.io/translate).
