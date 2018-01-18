Rechte lijnen tekenen
:::::::::::::::::::::

Nu we tina hebben gemaakt is het tijd om tina wat te laten doen. Met de opdracht ``tina.forward(100)``, gaat tina 100 stappen vooruit.

Voer de code uit met ``Run``. Als je het de eerste keer niet goed kunt zien --het duurt soms even voordat tina zichtbaar wordt-- kun je de code altijd gewoon nog een keer met de uitvoeren.

Je kunt tina natuurlijk ook achteruit laten lopen door ``tina.backward`` te gebruiken (i.p.v. ``tina.forward``). Pas de voorbeeldcode zo aan dat tina nu 100 stappen achteruit loopt. Ga daarna door naar de volgende pagina.


.. activecode:: od-vb_tina.forward
   :caption: 100 stappen vooruit
   :nocodelens:
   :language: python

   import turtle
   tina = turtle.Turtle()
   tina.shape("turtle")

   tina.forward(100)
