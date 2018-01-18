Functies
::::::::

Je kunt met behulp van een *functie* een stukje code newaren voor later. Dit doe je door het stukje code in te springen en te beginnen met ``def`` functienaam ``():``. Vervolgens kun je met **functienaam** ``()`` het stukje code hergebruiken.

Probeer de onderstaande code maar eens uit en klik dan op de pijl om naar de volgende stap te gaan.


.. activecode:: functies-vierkant
   :caption: Vierkantjes
   :nocodelens:
   :language: python

   import turtle
   tina = turtle.Turtle()
   tina.shape("turtle")

   def vierkant():
       for i in range(4):
           tina.forward(40)
           tina.right(90)

   for i in range(4):
       vierkant()
       tina.right(90)
       tina.forward(15)
