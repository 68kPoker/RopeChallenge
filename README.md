# RopeChallenge
Rope challenge implemented in AdvSys

Proper solution located in file `Rope.adv`.

The `objects.adi` is a standard AdvSys library (provides basic room/thing and action definitions).

Here's the transcription of the test:

<pre>
Rope challenge!
Blue room.
You are in blue room with calm ocean water. You can travel south to the green
room. There's a suitcase here. There's a piece of rope here.
:get suitcase and one end
suitcase taken.
one end taken.
:south
Green room.
You are in green room with green grass. The blue room can be seen to the north.
The yellow room is located to the south.
:south
Yellow room.
You are in yellow room with sun-shine light. There's an exit to the north
leading to green room.
:north
Green grass room
:look
Green room.
You are in green room with green grass. The blue room can be seen to the north.
The yellow room is located to the south. There's other end of a rope here.
:south
Yellow sun room
:tie one end to suitcase
You tied the suitcase to one end of a rope.
:drop one end
one end dropped.
:north
Green grass room
:get other end
other end taken.
:north
Blue water room
:south
Green grass room
:look
Green room.
You are in green room with green grass. The blue room can be seen to the north.
The yellow room is located to the south. There's one end of a rope here
(attached to suitcase).
:untie one end
You untied the suitcase from it.
:quit
Are you sure you want to quit? y
</pre>
