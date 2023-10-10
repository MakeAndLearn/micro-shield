Programació elements de la placa
=====


Brunzidor
------------

El brunzidor de la micro:shield està connectat al pin 0 de la placa micro:bit. En les plaques micro:bit V2 ja disposem de brunzidor integrat, en el cas de les micro:bits V1 s'utilitzarà el brunzidor de la micro:shield.

Per programar aquest element utilitzarem els blocks de l'apartat music.

(imatge)

Seguidament podem veure un exemple de programació perque soni una melodia amb el brunzidor.

.. raw:: html

  <div style="position:relative;height:calc(300px + 5em);width:100%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/---codeembed#pub:S40216-52246-16388-51582" allowfullscreen="allowfullscreen" frameborder="0" sandbox="allow-scripts allow-same-origin"></iframe></div>


LEDS RGB
------------

Els leds de la placa micro:shield es troven a la part frontal de la mateixa. Disposem de 4 leds RGB connectats al pin 16 de la micro:bit. Aquests leds es programen mitjançant la llibreria neopixel que podem trobar a extensiones.

Importació de la llibreria
------------
Clicar a l'apartat de programació "extensions".
(imatge)
Escriure el nom de l'extensió, neopixel, en el cercador.
(imatge)
Sel·leccionar la llibreria.
(imatge)
Ja tenim els blocs disponibles a l'apartat de neopixel.

Programació dels leds
------------
El primer pas essencial és declarar els leds que tenim connectats i els pins en que es troven amb el primer bloc de l'apartat neopixel.

.. raw:: html

  <div style="position:relative;height:calc(300px + 5em);width:100%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/---codeembed#pub:S79837-81525-51896-16811" allowfullscreen="allowfullscreen" frameborder="0" sandbox="allow-scripts allow-same-origin"></iframe></div>

Després de programar això ja podem programar els leds de la micro:shield. Seguidament trobem diferents exemples:

- Programa d'arc de sant martí

.. raw:: html
  
  <div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:S07748-02339-99765-82302" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>

- Encendre els 4 leds d'un color

.. raw:: html

- Encendre 1 led d'un color

.. raw:: html

- Pampallugues de colors

.. raw:: html
