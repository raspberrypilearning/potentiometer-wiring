Tu auras besoin de :

+ Un Raspberry Pi Pico
+ Un potentiomètre
+ 3 x fils de liaison prise-prise

Un **potentiomètre** a trois broches :
- Masse
- Signal analogique
- 3V3 (alimentation)

Lorsque le potentiomètre est tourné à fond vers la **gauche**, la flèche pointe vers la broche **GND**, lorsqu'il est complètement tourné vers la **droite**, la flèche pointe vers la broche **3V3**. La broche du milieu est la broche à partir de laquelle le Raspberry Pi Pico lit une valeur.

![Une illustration d'un potentiomètre.](images/potentiometer-illustration.png){:width="400px"}

**Branchement :** Trouve trois fils de liaison pris-prise et attaches-en un à chaque broche du potentiomètre. Tu voudras peut-être fixer les broches avec du ruban électrique si elles te semblent lâches.

Branche l'autre extrémité de chaque fils de liaison au Raspberry Pi Pico :

+ Branche la broche marquée d'un petit 1 à la broche **GND** entre **GP21** et **GP22**.
+ Branche la broche du milieu au **GP26_A0**. C'est une broche analogique.
+ Branche la broche marquée d'un petit 3 à la broche **3V3**.

![Un potentiomètre relié à un Raspberry Pi Pico.](images/pot-diagram.png)