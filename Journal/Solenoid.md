# Winding, baby!
Happy to see that you're still reading, last time I promised that we'd wind some spools. 

Today will be all about winding! **At least so I thought**



There's generally two ways to controll the coils, one using pwm and the other entirely mechanical. I have used pwm previously so I opted for the mechanical way.

Anyways, lets discuss how coils work and why I bought two sets of copper wire.


When passing a current through the coil two important things will happen, a magnetic field will be created and heat will be generated.

The stronger current passed through the coil the more heat will be generated, and we want a pretty strong one. The only problem with this is that the heat will eventually (pretty quickly as I have discovered) melt the plastic and thus destroy the spool.

# How do we work around the heat problem?
Counter-intuitively solenoids become weaker with more turns of the coil! Confusing at first but it is simply due to the resistance getting higher with a longer wire.

Alright, easy peasy! We increase the numbers of turns on the coil..... Wait, that also reduces the power of the coil.

Guess it wasn't so easy. 
Okay, then what about this, coils that are 'one shot' as in only activated very briefly (such as shingshot and bumper) can be ignored, let's wind those to get the most power. We are currently more interested in the coils that need a 'hold' function, or in other words to be continousley used, but we also want them to have the power of a 'one shot' coil.

Any ideas?

Well, let's do both! We wind these coils with a strong (one shot) coil AND a weak (hold) coil. When activating the flipper we pass current in only the 'one shot' coil untill the flipper is fully extended, then we connect the weak coil in series to increase the resistance within the entire solenoid, reducing the power and heat generated. As the coil doesn't need to have a lot of power when fully extended, just enough to hold a ball up, this works superb!
(I should add that this is not my idea, this is how flipper solenoids usually work (unless doing pwm))

Okay! Sounds like a plan, we'll figure out how to connect the different coils later on, for now let's do some winding! :D


# Many hours later!
We saw the spool bobbin in the last chapter, but now there's wire on it too. Fancy!
![Image of the first coil](https://i.imgur.com/TaxWT8W.jpg)


As the header suggests this took far longer than expected, IIRC it took 2 hours and I don't feel like doing this again.

If I sound disheartened it's because I am! However, the solution to any problem is innovation, and it shal prevail!

# Enter coil winder
![Coil winder](https://imgur.com/zIKc4Ku)

Why spend 2 hours doing a task when I can spend the entire day automating it!
There's really not too much to say about this thing. It's connected to a drill and makes my life a lot better! 3D model files can as always be found in /Models directory.

# I digress
Let's go back to the solenoids.

I wound two of them initially, with 400 and 600 turns respectively. When I got something working I'll test their strengths and decide exactly how many turns I want them to be.
That number wasn't pulled right out of my ass though, I got it from here: (Pinballmedic)[https://www.pinballmedic.net/coilchart.html] 
**WARNING**: Not for the faint of heart! 

But perhaps the most important thing to take away from that website is this: "It's not that important", coils on the website have pretty much all different wire dimensions and combinations of them. This is where I got the wire dimensions for the copper wire, I got most of my insperation from the Williams flipper coils because, convieniently, they advetrised the strength of the flippers (thank heaven for some understandable information in this sea of clutter!). 

I also got my power supply to almost match this specification. The Williams coils use 50V, and I got mine with 48V, close enough. I bought the beefiest supply I could find (which was still affordable) with 20 amps, netting a solid 1000 watts. (I guess that means 20.8 amps but don't be that guy)

# Two months wait for the delivery and we're finally ready to launch!
![Shit](https://imgur.com/9eK84gB)

**Shit**

It moves ever so slightly and then my power supply turns of. With some answers in the pinside forum it seems like my power supply can't handle the change of voltage or something like that (I'm not quite sure yet) and from the power supplys perspective this seems like a short, it then turns of to protect itself.

It was then recomended to me that I should use a capacitor bank connected before the solenoid.

Alright, see you when the shipping is done :(


Thanks for reading part[1]