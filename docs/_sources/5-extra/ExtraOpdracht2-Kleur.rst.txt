Challenge 2: Een tekening met kleur
:::::::::::::::::::::::::::::::::::

Een mooie tekening is niet compleet zonder kleur. Bij deze tekeningen kun je twee aspecten kiezen, de kleur van de lijn (ofwel de "pen") en de opvulling. Beide zijn standaard zwart ("black").

De lijnkleur veranderen doe je net als het kiezen van een andere pen door op het moment dat je van kleur wilt wisselen het commando ``pencolor(`` kleur ``)`` te geven.

Je kunt ook je tekening met kleur opvullen. De kleur stel je op eenzelfde manier in als de penkleur (met het commando ``fillcolor(`` kleur ``)``) maar hier moet je tijdens het tekenen ook aangeven wanneer je begint met opvullen, dit doe je met ``begin_fill()``, en wanneer je stopt met opvullen, met ``end_fill()``. Probeer in het onderstaande voorbeeld deze commando's op andere plaatsen te zetten.

Overzicht commando's
--------------------

``tina.forward(`` afstand ``)``
  beweeg tina **afstand** stappen naar voren
``tina.backward(`` afstand> ``)``
  beweeg tina **afstand** stappen naar achteren
``tina.left(`` hoek ``)``
  draai tina **hoek** graden naar links
``tina.right(`` hoek ``)``
  draai tina **hoek** graden naar rechts
``for i in range(`` aantal ``):``
  herhaal de daarna *ingesprongen* commando's **aantal** keer
``def`` functienaam ``():``
  hiermee *definieer* je een stukje code dat je later kan hergebruiken door alleen **functienaam** ``()`` te typen
``pencolor(`` kleur ``)``
  verander de lijnkleur naar **kleur**. Gebruik hiervoor de Engelse naam voor de kleur tussen aanhalingstekens, bijvoorbeeld ``"red"``, ``"orange"``,  ``"green"``, ``"pink"`` of ``"yellow"``.
``fillcolor(`` kleur ``)``
  verander de opvullingskleur
``begin_fill()``
  begin vanaf hier op te vullen
``end_fill()``
  stop hier met opvullen

Opdracht
--------

Teken nu een huis met de turtle. Je mag de grootte en de kleur zelf bepalen, onderstaande tekening is slechts een (saai) voorbeeld.

.. image:: images/huis.png

.. activecode:: opg-statements-huis
   :caption: Balans
   :nocodelens:
   :language: python
   :enabledownload:

   import turtle
   tina = turtle.Turtle()
   tina.shape("turtle")
