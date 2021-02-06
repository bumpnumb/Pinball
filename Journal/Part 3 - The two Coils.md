Hi, it is me again!

Today is finally the day! I have mentioned the multiple coils several times now, today we are finally making them.


Let us first recap why we need them:
 - Coils heat up

That simple really, and as we already talked about we reduce the generated heat by increasing the resistance through the solenoid.

This is an updated diagram from the last entry:
![](https://raw.githubusercontent.com/bumpnumb/Pinball/main/Images/Wiring_diagram_2.png)

We now see two coils, both are in the same solenoid though.

We can alse see the switch next to the second coil, we want this switch to be normally closed allowing the current to pass through the first coil, then skip the second coil due to the short at the switch. This will work as out initial power surge, the kick, and when the flipper is fully extended we open the switch, increasing the resistance, allowing for the hold power to keep the flippers up for an increased duration.

Right, winding the coil is easy peasy thanks to the coil winder we saw in part[1].
The harder part in this chapter will be creating and adjusting the switch.

Let us start out by having a look at how this is done in the wild, this is where I got my inspiration from:
![](https://www.marcospecialties.com/pinball-parts-blog/wp-content/uploads/2020/06/eos-switch-flippper-coil-marco-pinball.jpg)

I do not think there is too much to discuss about the mechanics in this illustration. However, I can clarify that EOS means End Of Stroke, and instead of fully extended I will from now use this abbreviation.

I took a nummber of crude measurements and came up with this print:

![](https://raw.githubusercontent.com/bumpnumb/Pinball/main/Images/Flipper_joint.PNG)

I highlighted the part that will interact with the switch.

Okay, the joints have been modified to interact with the switch, now comes the switch.

Real ones look more or less like this:

![](https://www.marcospecialties.com//images/products/ASW-A1-162/large.JPG)

You know the rules though, no buying complete parts! So I ordered a copper sheet with 1mm depth. **This was way too thick!**

I then cut it into a crude shape and designed an assembly/mount for it, eventually the mount got integrated into the solenoid mount:

![](https://raw.githubusercontent.com/bumpnumb/Pinball/main/Images/EOS_assembly.png)

I highlighted the eos mount on the solenoid mount.

Right, time to assemble everything. 

![](https://i.imgur.com/5hWxXiZ.jpg)

Easy enough, things go so fast when there is no delivery to wait for!

Remember what I said about the difficulties with soldering thick wire, you can multiply that by a factor of ten when it comes to a solid chunk of copper!
I had to clamp the copper piece in my vice, heat my soldering iron to the max and start of with just heating the copper enough to a state where the solder did not instantly solidify at contact.

Anyways it went pretty well and everything is now assembled, let us try it out!

![](https://raw.githubusercontent.com/bumpnumb/Pinball/main/Images/First_eos_test.gif)

Looks pretty good, now it is just to connect the different coils and see if it overheats. **Note**: The switch is connected in the wrong orientation in this gif, being like this it is not normally closed like we need it to be. The next gifs will have the switch in the correct orientation!


# Oops!

From the previous gifs of the solenoid in action you might have seen that I do not have a switch in which to activate the solenoid with, I have just connected two wires together.

Well, I was testing the solenoid and the wires welded together, this caused the solenoid to overheat and the plastic melted. 

I find it funny that this is the exact problem that we are trying to work around and it happens during testing...

Well, no worries, I had another coil.

So far we had been using the 600-turn coil. And now we will start using the 400-turn one.

**Immediate problem**: 
Remember that the coil becomes stronger with fewer turns? If not this might be a friendly reminder:

![](https://raw.githubusercontent.com/bumpnumb/Pinball/main/Images/Solenoid_breaking_1.gif)

It instantly broke the joints. Worry not, we will just print some beefier ones. I am still trying to avoid using metal as much as I can. But I can see that it might have to be used in some places... **foreshadowing :)**

Anyways, one print later and we got this:

![](https://raw.githubusercontent.com/bumpnumb/Pinball/main/Images/Solenoid_working_4_slowmo.gif)

Looks good I thought. There are some oscillations, but I think those are due to the second coil being too weak, I wound that one with 1700 turns. For my next attempts I will reduce the number of turns on the second coil, perhaps to something like 1000 or 1200, or maybe I will create a setup to test multiple configurations, keep reading to find out what I did :)


# Help from an unexpected hand

I uploaded these gifs to imgur so show friends and family (I had talked about this at work for about half a year by this point and still had nothing to show) and some people commented on my gifs. How about that? I did not know that anyone casually browsed imgur for images, guess I was wrong again :)

Anyways some people commented that the sparks were an issue that had to be fixed or the switches would eventually stop working. They recommended (among other ideas) to use TVS diodes. They are components used to reduce high voltage peaks, which would in theory remove the sparks.

I also had a look at the real leaf switches, they use contact points with silver or tungsten. I figured it was a good idea to get a few of those too, they were a lot harder to get compared to the diodes (which I got from digikey), I ended getting a few from [PBresource](http://www.pbresource.com/pfswitch.htm#common).

This is where we are right now, waiting for deliveries again.

I will now take a break from the flippers, I consider them to be pretty much done except for the diodes and contacts, but hopefully with them the sparks will be gone and they will be completed.

So next time I will talk about the slingshots, since they do not need the EOS switches.

Thanks for reading part[3]







