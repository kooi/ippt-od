Samenvatting herhaling
----------------------

``tina.forward(<afstand>)``
  beweeg tina <afstand> stappen naar voren
``tina.backward(<afstand>)``
  beweeg tina <afstand> stappen naar achteren
``tina.left(<hoek>)``
  draai tina <hoek> graden naar links
``tina.right(<hoek>)``
  draai tina <hoek> graden naar rechts

Hieronder staan een aantal beginnetjes code en een voorbeeldfiguur. Pas de code telkens op zo'n manier aan dat de turtle de figuur tekent. De afmetingen staan in de figuur vermeld, die getallen hoef je er dus niet bij te zetten.

Opdracht: Teken een vierkant
----------------------------

.. image:: images/square-200.png

.. activecode:: oefen-statements-square
   :caption: Vierkant
   :nocodelens:
   :language: python
   :enabledownload:

   import turtle
   tina = turtle.Turtle()
   tina.shape("turtle")

   tina.forward(200)
   tina.left(90)
