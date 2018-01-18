Opdracht 2: Zeshoek
:::::::::::::::::::

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

Hieronder staan een aantal beginnetjes code en een voorbeeldfiguur. Pas de code telkens op zo'n manier aan dat de turtle de figuur tekent. De afmetingen staan in de figuur vermeld, die getallen hoef je er dus niet bij te zetten.

Opdracht: Teken een regelmatige zeshoek
---------------------------------------

Teken een regelmatige zeshoek (elke hoek *in* de zeshoek is 120 graden, je moet dus telkens 60 graden draaien) met behulp van een loop. Als je klaar bent kun je met de Download je programma downloaden (je moet dan wel daarna op "Behouden" klikken).


.. image:: images/hexagon.png

.. activecode:: oefen-statements-square
   :caption: Zeshoek
   :nocodelens:
   :language: python
   :enabledownload:

   import turtle
   tina = turtle.Turtle()
   tina.shape("turtle")
