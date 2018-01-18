Draaien
:::::::

Als we ergens naartoe willen gaan dan kunnen we natuurlijk niet alleen voor- of achteruit, dan zullen we ook moeten draaien. Je kunt tina vertellen om naar rechts te draaien met het commando ``tina.right()``. Je geeft dan tussen haakjes aan hoeveel *graden* je wilt draaien.

Een heel rondje is 360 graden, dus als je een kwartslag naar rechts wilt gebruik je ``tina.right(90)``.

Pas de code nu aan opdat tina precies omdraait.

Als je naar rechts kan draaien, dan kun je uiteraard ook naar links draaien. Dat doe je met de functie ``tina.left``. Pas de code nu aan zodat tina een bocht naar links maakt.

Als je door blijft draaien kom je uiteindelijk weer in je originele positie terecht. Pas de code nu zo aan dat tina eigenlijk 90 graden *naar rechts* gedraaid is. Ga daarna door naar de volgende pagina.


.. activecode:: od-vb_tina.right
   :caption: Rechts afslaan
   :nocodelens:
   :language: python

   import turtle
   tina = turtle.Turtle()
   tina.shape("turtle")

   tina.right(90)
