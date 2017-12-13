Rechte lijnen tekenen
:::::::::::::::::::::

Nu we tina hebben gemaakt is het tijd om tina wat te laten doen. Met de opdracht ``forward(100)``, gaat tina 100 stappen vooruit. We moeten dan wel zeggen dat het tina is die 100 vooruit moet, dus dan wordt dit: ``tina.forward(100)``.


.. activecode:: od-vb_tina.forward
   :caption: 100 stappen vooruit
   :nocodelens:
   :language: python

   import turtle
   tina = turtle.Turtle()
   tina.shape("turtle")

   tina.forward(100)


Je kunt tina natuurlijk ook achteruit laten lopen door ``tina.backward`` te gebruiken (i.p.v. ``tina.forward``). Pas de voorbeeldcode zo aan dat tina nu 100 stappen achteruit loopt.
