Herhaling (iteration)
:::::::::::::::::::::

Je hebt als het goed is net een programma gemaakt waarmee je tina een vierkant laat tekenen; dat zag er waarschijnlijk ongeveer als volgt uit:

.. activecode:: vb-iteration-square
   :caption: Een vierkant met zijde 100
   :nocodelens:
   :language: python

   import turtle
   tina = turtle.Turtle()
   tina.shape("turtle")

   tina.forward(100)
   tina.right(90)
   tina.forward(100)
   tina.right(90)
   tina.forward(100)
   tina.right(90)
   tina.forward(100)
   tina.right(90)

Merk op dat de twee commando's ``tina.forward(100)`` en ``tina.right(90)`` vier keer worden herhaald!
Dit kunnen we overzichtelijker en efficienter opschrijven door gebruik te maken van een *herhaalinstructie*; dit wordt ook wel een *loop* (het Engelse voor lus) genoemd.

We schrijven dan ``for i in range():``, het getal dat je dan tussen de haakjes zet is het aantal keer dat de daaropvolgende commando's worden herhaald.

.. activecode:: vb-iteration-square2
   :caption: Een vierkant met zijde 100 *met herhaling*
   :nocodelens:
   :language: python

   import turtle
   tina = turtle.Turtle()
   tina.shape("turtle")

   for i in range(4):
       tina.forward(100)
       tina.right(90)


De for-opdracht zorgt ervoor dat de twee opdrachten eronder vier keer worden uitgevoerd. Als er ``for i in range (14)`` zou staan bijvoorbeeld, dan zouden die twee opdrachten 14 keer worden herhaald. Let wel op dat je eerst 4 spaties plaatst voor de opdrachten die herhaald moeten worden, dit noem je *inspringen*.
