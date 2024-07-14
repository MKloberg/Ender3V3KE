# Ender3V3KE
Some Thoughts and Personal Notes about the Creality Ender3 V3 KE

This is an amazing machine and a great low cost printer to get started in the world of 3D printing.
I'm not that seasoned in 3D printing yet (2 years so far), but have been on an ongoing voyage to research, design and implement solutions to problems that the Creality printers have to better my own situation and to help others.

My first printer/project was the Creality Ender3 S1 Pro.
It was very evident to me from the start that this printer had an inadequate part cooling system, which prevented it from reaching its true protential.
After over a year, relearning CAD in F360 and Solidworks, this solution emerged: https://www.printables.com/model/511962-taurus-v5-cooling-duct-for-creality-sprite-extrude
We can now print a perfect benchy in under 16 minutes, mission accomplished: https://www.youtube.com/watch?v=UUEOKS9140g&t=1s
This was sort of my apprentice project into the community, I had times where I thought to go commercial with it but since that has been such a game changer for 100's of users, I still keep it available for free for anyone.
V5 of the Taurus marks my departure from this type of research and optimization work, markets are shifting and may not need people like me to make a difference anymore.

With that working very nicely, I decided to get into side hustle 3D printing to see where that might go to make a few bucks on the side.
This is when the Bambu Craze started happening, which I never bought into. It's a lot of cash to bank out and eventually has its own problems. Still a good solution for people that print something maybe once a week.
This is not my use case, we'll be printing 24/7 on multiple printers.
I'd rather have have four working printers that I can fully understand, have parts available instantly for the same price that one X1C actually is, let alone the AMS.

For farming, cost of ownership / the cost to aquire another profit node is crucial, which for me meant finding the lowest cost printer in aquisition that has all the features that I added on my previous E3S1Pro.
It doesn't take much guess work to figure out what that was:
- No more sonic pad. Integrated full Klipper, but not on shared instances. One Klipper, per unit.
- Good part cooling, out of the box. (no Taurus needed)
- A solid, tried and true extruder (more on that later)
- A camera with spaghetti detection.
- No rollers, linear rails instead.
- Auto Z-offset (more on that later)

One of the printers that meet all these requirements to some extent is the Creality Ender3 V3 KE.

Now that you know where I'm coming from, let's talk about the problems that I ran into so far and how to fix these to make this printer a reliable workhorse:

1. The factory PEI sheet it comes with is junk.
Once you receive your new Creality Ender3 V3 KE, I urge you to put the PEI sheet right then and there into the nearest trash container, because it is utterly bad. It's too coarse and if you choose to accept this will fight this for a few months (as I did).
Instead, get one of the golden standard sheets that are readily available: https://www.amazon.com/gp/product/B0BRCRX6T9

2. The 2510 hotend fan is junk.
About a month or so into heavy printing, you may notice some strange whirring sounds on the start of a print.
There are countless reports on this now and people are even saying this is normal. I can assure you that it isn't.
This sound comes from the bearings falling apart in this fan and unless it is fixed, print quality will drop progressively. The heat break wants adequate cooling which it is not getting if you ignore this.
The most cost effective solution I found so far was to get these fans, clip off the cable of the old fan and solder the two wires (red<>red/black<>black) togehter to restore it to a working unit.
https://www.amazon.com/dp/B07KS5P1KV 
There are two versions of this 2510 fan, a hyraulic bearing version and a ball bearing version, the recommendation is the ball bearing version of the fan because it has a longer life span (50,000 hours).

3. 







