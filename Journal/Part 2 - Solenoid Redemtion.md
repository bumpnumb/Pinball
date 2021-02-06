Hi again dear reader!

Last time we ended with a wild rage from seeing the solenoids not working! Let us reverse the tape a bit and take a calmer approach to this!


# Why did the solenoid not work?
With a closer look at the video from the last entry we see that the solenoid is in fact working, there is movement.
![](https://raw.githubusercontent.com/bumpnumb/Pinball/main/Images/Shit.gif)

Sorry for the shaky camera, me and my SO were quite scared when connecting this for the first time, high current involved, fire extinguisher was present :D

Anyways, let us calculate the current drawn by the solenoid to see if we simply do not have enough in our power supply.

A quick sketch gets us to something like this:
![](https://raw.githubusercontent.com/bumpnumb/Pinball/main/Images/Wiring_diagram_1.png)

Do not mind the diode next to the coil, I will try to explain why it is there later.

The power supply is rated for 20 amps so this should not be a problem, right?
With some advice from pinside and reddit I bought some capacitors to ease the initial load on the power supply.
I also learned about a magical component which I bought too.

The NTC thermistor! It is a resistor which has a relatively high resistance at room temperature, but when heated up (such as when it resists electricity) it greatly reduces the resistance. Basically it is a startup-resistor. 

We are going to have a big capacitor bank so throwing in one of these is a good idea.

Alright, now we wait for the delivery!

# Parcel recieved, time to build!
By the magic of internet time travel it arrived in what seems to you just a few seconds, witchcraft!

The parts have arrived and I grab ye olde soldering iron.

![](https://i.imgur.com/2ZTXd5v.jpg)

Here we have the parts all together. It is harder than I expected to solder large wires, they dissipate so much heat so the solder cools quite fast. I am learning and I think it is visible :)

The thermistor was a lot larger than I expected, it feels like some ancient technology. It is 20mm in diameter, quite the difference from the parts I have used in the past.

Let us hook this up and see if it works!


# It works!
![](https://raw.githubusercontent.com/bumpnumb/Pinball/main/Images/Solenoid_working_1.gif)

Wow, what a feeling!

Have you ever climbed a mountain? If so, did you take any pictures of the amazing landscape? or the immesurable size of the mountain before you?
If you have, as I have, you know that the sheer magnitude of the mountains size never looked as amazing when showing it to your friends and family. You tell them that it was so large they can not imagine by the image, and they would understand if they were there.

The same goes for this gif, the feeling I felt when it worked after months of building, failing and waiting is my mountain, I just climbed a mountain.


Let us watch this in slowmotion too.
![](https://raw.githubusercontent.com/bumpnumb/Pinball/main/Images/Solenoid_working_1_slowmo.gif)

I can stay here and watch this gif the entire day but let us move along.

The solenoid is now working and it is time to create the housing and the links for the flipper. 
You may have noticed that I talked a bunch about using two coils for the flipper solenoids and we'll get there, they can wait untill we have solved the switching of them.


A few iterations later (and probably not the last one) I ended up with a design like this:
![](https://raw.githubusercontent.com/bumpnumb/Pinball/main/Images/Flipper_mount.PNG)

I took heavy insperation from this image:
![](https://www.marcospecialties.com//images/products/500-5177-01/large.jpg)

The prints took a few hours each but it was a pleasant experience, I printed during the days when I was working and tested/redesigned during the evenings.

This is how it ended up all connected:
![](https://raw.githubusercontent.com/bumpnumb/Pinball/main/Images/Solenoid_working_2_slowmo.gif)

I put a piece of tape to highlight the rotation.

**Note**: You might be able to tell that this is not the same print as I just advertized, this is correct. This gif is taken during the testing stages, however, the current design works in just the same way.


Let us view a final gif where a flipper is connected before we end this chapter:
![](https://raw.githubusercontent.com/bumpnumb/Pinball/main/Images/Solenoid_working_3_slowmo.gif)

Here we can see the range of the flipper, which I think is pretty good, and if I want to change it I can either reduce the length of the base plate (leaving less space for the iron rod to move) or change the length of the joints connecting the iron rod to the flipper.


It feels really good to have something working!
Next time we will have a look at that other coil I have been mentioning.
Thanks for reading part[2]!