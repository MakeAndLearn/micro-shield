Programació d'elements en els diferents connectors
=====

Per utilitzar els pins d'entrada o sortida digital podem utilitzar els pins indicats en la imatge.

(imatge)

Cada pin té el seu nom a la part superior, exemple P7. Els pins grocs funcionen amb un voltatge de 3,3V. Els pins blaus poden funcionar a 3,3V o 5V. Això es configura manualment a través de l'interruptor indicat.

(imatge)

Per programar aquestes sortides podem utilitzar els blocs de l'apartat pins. 

Entrades/sortides digitals
------------

- En aquest codi activem i desactivem la sortida durant 1 segon.

(codi)

- En aquest  codi activem una sortida analògica en diferents valors. Cada valor està activat 1 segon.

(codi)

Entrades/sortides analògiques
------------

- En aquest codi es mostra la lectura digital del pin 4 per la matriu de leds de la micro:bit.

(codi)

- En aquest codi es mostra la lectura analògica del pin X per la matriu de leds de la micro:bit.

(codi)

Servos
------------

Per utilitzar servos amb la placa micro:shield els connectarem als pins indicats en la imatge.

(imatge)

Els servos els podrem programar mitjançant els blocs de servo de l'apartat de pins o el bloc de servo de la llibreria micro:shield.

- Programa de moviment del servo en 3 posicions utilitzant blocs de l'apartat pins.

(codi)

- Programa de moviment del servo en 3 posicions utilitzant blocs de la llibreria microshield.

(codi)

Motor DC
------------

El motor DC es connecta a la microshield en els connectors indicats en la imatge.

(imatge)

La micros:shield disposa de quatre ports de M1 a M4 amb dos connectors etiquetats cada un amb els signes + o -. Els motors DC funcionen amb dos cables un negre i un vermell. Utilitzarem un tornavís pla per fixar els cables en el connector. Preferiblement, connectarem el cable vermell al connector amb el signe + i el cable negre en el connector amb el signe -.

(video/giff)

Per programar els motors haurem d'importar la llibreria de la micro:shield.

- Programa per activar el motor en un sentit de gir

(codi)

- Programa per aturar el motor.

(codi)

- Programa que activa el motor en un sentit de gir durant un segon, l'atura durant un segon i l'activa en l'altre sentit de gir durant un segon.

(codi)


Motor pas a pas
------------

El motor pas a pas es connecta a la microshield en els connectors indicats en la imatge.

(imatge)

La micros:shield disposa de dos connectors de motor pas a pas. 

Per programar els motors haurem d'importar la llibreria de la micro:shield.

- Programa per fer girar el motor 90º.

(codi)

- Programa per fer girar el motor 180 passos.

(codi)

I2C
------------

Els components I2C es poden connectar en els connectors indicats en la imatge.

(imatge)

Depenent del component utilitzat s'haurà d'importar la seva pròpia llibreria per poder programar-lo.
