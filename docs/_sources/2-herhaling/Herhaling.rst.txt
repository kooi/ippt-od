Herhaling
:::::::::

Je hebt als het goed is net een programma gemaakt waarmee je tina een vierkant laat tekenen; dat zag er waarschijnlijk ongeveer als volgt uit:


.. code-block:: python

   import turtle
   tina = turtle.Turtle()
   tina.shape("turtle")

   tina.forward(150)
   tina.right(90)
   tina.forward(150)
   tina.right(90)
   tina.forward(150)
   tina.right(90)
   tina.forward(150)
   tina.right(90)

Merk op dat de twee commando's ``tina.forward(150)`` en ``tina.right(90)`` vier keer worden herhaald!
Dit kunnen we korter opschrijven door gebruik te maken van een *herhaalinstructie*; dit wordt ook wel een *loop* (het Engelse woord voor lus) genoemd.

We schrijven dan ``for i in range():`` voor de commando's die we herhaald willen hebben; het getal dat je dan tussen de haakjes zet is het aantal keer dat de commando's worden herhaald.

In dit geval willen we ``tina.right(90)`` en ``tina.forward(150)`` allebei vier keer herhaald worden. We plaatsen dan na ``for i in range(4):`` deze twee commando's. Om aan te geven wat er herhaald wordt plaatsen we voor die commando's vier spaties, dit noem je *inspringen*.

Voer onderstaande code uit en ga daarna door naar de volgende pagina.

.. activecode:: vb-iteration-square
   :caption: Een vierkant met zijde 150 *met herhaling*
   :nocodelens:
   :language: python

   import turtle
   tina = turtle.Turtle()
   tina.shape("turtle")

   for i in range(4):
       tina.forward(150)
       tina.right(90)
