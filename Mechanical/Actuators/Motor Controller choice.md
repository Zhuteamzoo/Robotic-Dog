# Motor Controller Choice (and Encoder)

I found 2 main options for my motor controller FOC.

---

Odrive S1: https://shop.odriverobotics.com/products/odrive-s1


Moteus r4.11: https://mjbots.com/products/moteus-r4-11

---


They both include On board encoders which is very helpful since I don't need to buy a seperate encoder. The Odrive S1 is 149 USD while the moteus r4.11 is only 59 USD.
The moteus r 4.11 comes with one of those little magnet thingies that we use for the encoder and it was designed for quadrupeds. Taking all of this into account I will be using the moteus r4.11 over the odrive S1.

---

## Limitations

The moteus's continuous phase current is 12A/32A (w/o thermal management, w/ thermal management). The motor that I found could take up to ~62A of continuous current so the power of my motor will be cut in half. On top of that, the moteus
will need to have some thermal management. There will be air vents for passive cooling, but there will also be other methods of cooling. I will try to not resolve to a fan or water cooling since that could get bulky really quick.
