
# Let's get started!
Where do we even begin... I think a good start is why I want to make a pinball machine!
I think it begun with an image like this:
![Image of pinball part](https://lh3.googleusercontent.com/proxy/3aMRH_PUUcJp-Ba_dLPP5OP7MFL-Rfubt07uwJyXcvG3z9zjtrJOyp1QxXFzm2kD1Gy_moHBQC2hg6xzEEs)

which lead me to reading some on the mechanics of pinball machines, who knew they run almost exclusively on solenoids?! I guess thats all I needed to become obsessed with pinball machines, or rather with the mechanics behind pinball machines.

This seems like a good moment to talk about what I expect to achieve with this project. If I'm being honest with myself, and perhaps more importantly now when I'm writing this to you, the reader, this project is doomed to fail just as so many others have since I'm more interested in the workings underneath a pinball machine rather than actually owning one. 
I'll still say the magic words though: "I will complete this project".

Before we go any further I want to step up the difficulty one level by adding a rule to the project:
**Any part that I can make on my own I will create myself**
However this does not mean I need to create my own metal sheets, or mine the ore required for that. Just that I won't buy parts half- or pre-assembled. For example: I will create my own spools for the solenoids. We'll get to those later on so don't worry if you dont know what that means.

Anyways, I digress...

 # It's decided
 I'm making my own pinball machine!
 First step is to create a solenoid. If you know as little about electronics as me you might ask yourself what a solenoid is. Worry not, I got you covered!
 ![Image of spool mechanics](https://www.justscience.in/wp-content/uploads/2017/05/HOW-DOES-A-SOLENOID-WORK.jpg)
 
 I won't go too much into detail, if you are interested: read up on it! It is a spool of insulated copper wire which creates a magnetic field when an electric current is applied, the magnetic field can then move a iron rod. This is the basic principle that powers the entire machine. The force of the moving iron rod is transferred into various motions that make the different parts of the machine move.

 Anyways, since I'm not allowed to buy a pre-assembled one I need copper wire!
 I could not find any place in Sweden that sold insulated copper wire in the quantities that I needed (and more importantly, as one continous wire. Soldering mid spool is a nono), at least not without getting some one-off deal with some company. I checked aliexpress which is my usual go-to when it comes to electronic parts but the price was surprizingly high and shipping was a no-go! Finally I found [ScientificWire](https://www.scientificwire.com/) which sold the right wire at what seemed like a decent price. There was just one little problem... The minimum order was quite large. 
 Well, some spare copper wire has never hurt anyone.
![Image of copper wire](https://i.imgur.com/JyKKtTa.jpeg)
Arduino pro micro for size reference. I'm using around 21 and 30 awg wire. (more on that later)

Guess I wont have to worry about running out of wire anytime soon :D
Anyways, wire ✔️

What more do we need?

`Power supply`

`Diodes`

`Wires`

`Iron rod`


I figured this would be the bare minimum needed to create a solenoid. **I was wrong**

The power supply was bought from aliexpress, wires were bought from a local store (Kjell & co) and I already had the diodes I needed. The iron rods proved to be elusive to me, some stainless steel rods will apparently work but will eventually become permanently magnetized and thus no longer work, I wanted the real deal. To make a already long story short, I got them quite expensivley from aliexpress.


Great now we got everything, lets go?

Not so fast young reader. We still need something to hold the copper wire on, a bobbin.

Luckily I own a 3D printer and with the dimensions from [Pinside](https://pinside.com/pinball/forum/topic/coil-dimensions) I swiftly recreated a solenoid bobbin:
![Image of bobbin](https://i.imgur.com/AErI18O.jpg)

Great! Now we can get somewhere!

**Note**: All 3D models can be found in the models directory.


Time to wind this bad boy.

Thanks for reading **part[0]**!