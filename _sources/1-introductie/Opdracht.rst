Opdracht
::::::::

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

Opdracht: Teken een vierkant
----------------------------

Hieronder staan een beginnetje van een programma en een voorbeeldfiguur. Pas de code aan opdat tina de figuur tekent. Als je klaar bent kun je met de Download je programma downloaden (je moet dan wel daarna op "Behouden" klikken).


.. image:: images/square-150.png

.. activecode:: opdracht-vierkant
   :caption: Vierkant
   :nocodelens:
   :language: python
   :enabledownload:

   import turtle
   tina = turtle.Turtle()
   tina.shape("turtle")

   tina.forward(150)
   tina.right(90)
