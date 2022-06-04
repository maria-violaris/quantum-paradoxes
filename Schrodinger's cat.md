# Schrodinger's cat, a different way of seeing things.
# 'Wave function collapse' or 'many worlds'
- 
- Since I don't speak English very well I wrote this article in Italian and then I used a translator.
So sorry for the mistakes.
- 
-
This is a small thought experiment that offers a different interpretation of Schrodinger's famous cat paradox.

To do this, I will simulate the experiment with the quantum computer that IBM makes available on the web.
This is the first step:

![g1](https://user-images.githubusercontent.com/25941322/149770634-c9441504-165a-44e7-a283-c9c072b003f2.gif)


We assume that the qubit q0 is the radioactive atom and the qubit q1 the cat, when q0 is | 0} the atom has not decayed, when it is | 1} it is decayed, when q1 is worth | 0} the cat is alive and when that is | 1} the poor cat is dead.

By inserting a Hadamard gate on qubit q0 we put it in a quantum superposition state (decayed, not decayed).

At this point we put the cat inside the box:

![g2](https://user-images.githubusercontent.com/25941322/149770692-3d41fa2b-ff10-4969-ae63-9a26ebf435c7.gif)


To simulate the introduction of the cat I put a control_X gate that has q0 as a control and q1 as a target, in this way, as can also be seen from the probability graph, if the atom does not decay q0 = | 0} the cat remains alive q1 = | 0}, if the atom decays q0 = | 1} the poor cat dies q1 = | 1}.

The radioactive atom and the cat (q0 and q1) are in quantum superposition and entangled each other (for us, outside the box, the cat is alive and dead at the same time).

After a few minutes we go to open the box to see if the cat is alive or dead, making a measurement of the qubit q1 (the cat) which will tell us if it is alive | 0}:

![g3](https://user-images.githubusercontent.com/25941322/149770752-0290f13f-66a0-4a83-9b13-a83cb964a855.gif)


Or if he is dead | 1}:

![g4](https://user-images.githubusercontent.com/25941322/149770788-4522e940-8fe3-4b91-b859-04aa923418f2.gif)


What happens is that when we open the box we collapse the wave function, which is in a superposition state (| 00} + | 11}), in one of the two states.

Now, however, let's try to see it from another point of view, we too become part of the experiment, at this point we are the qubit q2:

![g5](https://user-images.githubusercontent.com/25941322/149770827-37cc7d5a-38b0-4ebe-90c8-f0b41ef22e37.gif)


When we open the box and observe the cat we entangle with it:

![g6](https://user-images.githubusercontent.com/25941322/149770854-9d0e4d4e-63ff-4be2-be4b-f12f430a2061.gif)


And so when q2 is | 0} we are happy because we see the cat alive, when it is | 1} we are sad because we see the cat dead.

But which of the two conditions will we observe?

According to an observer outside our house, we are in superposition and entangled with the cat and the radioactive atom (| 000} + | 111}).

This is none other than the 'many worlds' interpretation, where there is no wave function collapse, but there are two parallel universes, one in which the atom has not decayed, the cat is alive and we we are happy.

The other in which the atom has decayed, the cat is dead and we are sad.

But, obviously, we cannot experience the two worlds at the same time, because there are 2 of us who cannot communicate with each other.

Which of the two interpretations do you prefer: the wave function collapse, or the many worlds?
