Opdracht: Vierkant
::::::::::::::::::

Maak een functie vierkant waarin je tussen de haakjes kan aangeven hoe groot het vierkant moet zijn. Je moet de functie dus als het volgt kunnen gebruiken:

.. code-block:: python

   vierkant(20)
   vierkant(50)
   vierkant(100)

et cetera.


.. activecode:: oefen-parameters-vierkanten
   :caption: ``vierkant()``
   :nocodelens:
   :language: python
   :enabledownload:

   import turtle
   tina = turtle.Turtle()
   tina.shape("turtle")
   tina.speed(10)

   def vierkant():
       for i in range(4):
           tina.forward(50)
           tina.right(90)

   vierkant(20)
   vierkant(50)
   vierkant(100)
